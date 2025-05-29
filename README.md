# Import-Fitbit-SpO2-data-into-Apple-Health
I created an Apple Shortcut that imports fitbit SpO2 (Blood Oxygen) data into Apple Health.

Steps:

1. Extract your Fitbit data using Google Takeout.
2. Locate the Minute SpO2 file: "Minute SpO2 - YYYY-MM-DD.csv" from the downloaded data.

   Takeout > Fitbit > Oxygen Saturation (SpO2)

3. Save/Move the csv files to iCloud drive.
4. On your iPhone, download [this shortcut](https://www.icloud.com/shortcuts/284b613fb2b74e4ba9c8b30bbe79b6cb).
5. On your iPhone, go to Settings > Apps > Shortcuts > Advanced, and enable "Allow Sharing Large Amounts of Data".
6. On your iPhone, open the Shortcuts app.
7. Click the three dots on the shortcut named "Log SpO2 to Health". 
8. Scroll down to where it says "Log Health Sample" and grant permissions to enter Blood Oxygen data
9. Click Done at the top
10. Run the shortcut, and when prompted for input file, select the csv file(s) you want to import from your iCloud Drive.


Note: I learned this method through [this post](https://discussions.apple.com/thread/255897572?sortBy=rank).

For anyone interested in creating similar shortcuts, below are the initial versions of the shortcut I made for debugging and testing purposes:

1. [Debug: Visually see the output at each action](https://www.icloud.com/shortcuts/c8c605be5f354c77ab3ad36910adadf9)
   
2. [Test: Import fewer lines and check on Health app](https://www.icloud.com/shortcuts/41c32edb1b0a4d8d91bf250d851aa1b5)

   
