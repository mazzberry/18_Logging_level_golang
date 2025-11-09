
## E-StackMarshaler

```Go  

zerolog.ErrorStackMarshaler = pkgerrors.MarshalStack
```
<br>

the ErrorStackMarshaler show us a clean log of what ever happened

<br>

## Log level 

<br>

```Go  

//-- log level
// trace
// debug
// info
// warn
// error
// fatal(critical)
// panic


```

<br>

```Go
zerolog.SetGlobalLevel(zerolog.InfoLevel)
```

<br>
<p>by this you can choose what stage of Crisis is important for u and it will show u that stage and above, not below</p>


