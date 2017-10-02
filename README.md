<H1>Send information to the new activity on android</H1>

```java
Intent intent = new Intent(getApplicationContext(), Main2Activity.class);
intent.putExtra("key",message);
startActivity(intent);
```

<h1>Read info from intent extra<h1>

```java
Bundle bundle = getIntent().getExtras();
if(bundle != null){
  String message = bundle.getString("key");
  Toast.makeText(getApplicationContext(),message,Toast.LENGTH_SHORT).show();
}
```
