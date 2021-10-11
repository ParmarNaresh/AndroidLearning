# Android basics using kotlin

## how to start activity?
 when you want to open any activity from activity.

```
val intent= Intent(this, ActivityName::class.java);
startActivity(intent)
```
You can also pass applicationContext instant of this

```
val intent= Intent(applicationContext, HomeActivity::class.java)
```

You can also pass data in intent

* value may be Boolean,Byte, Char, Short, Int, Long, Flot, Double, String?, Parcelable?, Serializable,Bundle? *

```
intent.putExtra("key","value")
```

You can get passed values from previous activity using intent.
```
val stringData=intent.getStringExtra("key")
```


        





