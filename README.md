# AndroidPassDataBetweenActivities

<H1>Send information to the new activity on android</H1>

'''java
Intent intent = new Intent(getApplicationContext(), Main2Activity.class);
intent.putExtra("key",message);
startActivity(intent);
'''
