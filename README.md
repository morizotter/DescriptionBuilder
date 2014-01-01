# DescriptionBuilder

This program was originally made by KISHIKAWA Katsumi. And I forked it. Because of the changes are a lot, I rewrited this README.

DescriptionBuilder is helper class to make easier implementing NSObject description method.
Or dump all instance variables of any object. 

## Usage

```
- (NSString *)description {
    return [DescriptionBuilder reflectDescription:self];
}
```

Or,

```
- (NSString *)description {
    return [DescriptionBuilder reflectDescription:self style:DescriptionStyleMultiLine];
}
```

Output:

```
<Settings: 0xd188b0; version = 100; autoLock = NO; twentyFourHourTime = YES; alarmSound = "digital-alarm"; alarmVolume = 1.000000>
```

## Author

**NAOKI MORITA(Forked)**
[http://moritanaoki.org/about](http://moritanaoki.org)

**KISHIKAWA Katsumi(Original)**
[http://d.hatena.ne.jp/KishikawaKatsumi/ (in Japanese)](http://d.hatena.ne.jp/KishikawaKatsumi/)

## License
The new BSD license