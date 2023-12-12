Грамматика НеМо:

### Test:

`(cond)?;` - работает как assert


### U
{body1} U {body2};

транслируется в 
```
0: if True then goto
1: {body1}

x: {body2}

```

