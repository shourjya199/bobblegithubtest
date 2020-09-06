oublic class Main
{
public void bobble
{
final GestureDetector gestureDetector=new GestureDetector(new GestureDetector.SimpleOnGestureListener()
{
public void onLongPress(MotionEvent e)
{
Log.e("","LongPress detected");
}
}
};
public boolean onTouchEvent(MotionEvent event)
{
return gestureDetector.onTouchEvent(event));
}
;
