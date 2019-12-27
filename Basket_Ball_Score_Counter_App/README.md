
# Basket Ball Score Counter
This file contains source code to my Basket Ball Score Counter App With:

## Instruction - To Run The App
1. Open Android Studio and make sure it is able to run its default program with no errors<br>
2. Replace default program code in the activity_main.xml file with the activity_main.xml code here<br>
3. Replace the code in the MainActivity.java file with the code found here in MainActivity.java<br>
4. Update the line in the MainActivity.java "package com.example.android.courtcounter;" with your own android studio package name. You may be required to update the line "import android.support.v7.app.ActionBarActivity;" with "import androidx.appcompat.app.AppCompatActivity;" depending on the version of android studio you are using. Doing the replacement will require you to also update the "ActionBarActivity" with "AppCompatActivity" in the "public class MainActivity extends ActionBarActivity {" code line<br>
5. In the MainActivity.java file comment out the portion of the code:<br>
    "@Override<br>
    public boolean onCreateOptionsMenu(Menu menu) {<br>
        // Inflate the menu; this adds items to the action bar if it is present.<br>
        getMenuInflater().inflate(R.menu.menu_main, menu);<br>
        return true;<br>
    }<br>

    @Override<br>
    public boolean onOptionsItemSelected(MenuItem item) {<br>
        // Handle action bar item clicks here. The action bar will<br>
        // automatically handle clicks on the Home/Up button, so long<br>
        // as you specify a parent activity in AndroidManifest.xml.<br>
        int id = item.getItemId();<br>

        //noinspection SimpSlifiableIfStatement
        if (id == R.id.action_settings) {
            return true;
        }

        return super.onOptionsItemSelected(item);
    }"
6. Replace the code in the styles.xml file with the code found here in styles.xml<br>
    
8. Run the app (program)<br>

## Basket Ball Score Counter App Output
![Screen Shot 2019-12-26 at 9 01 57 PM](https://user-images.githubusercontent.com/13493736/71500640-15a01300-2823-11ea-8027-de46acce43a5.png)
