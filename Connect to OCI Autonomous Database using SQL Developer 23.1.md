Connect to OCI Autonomous Database using SQL Developer 23.1

1. Browse [OCI](https://cloud.oracle.com/) at "Navigation Menu > Oracle Database > Autonomous Database > $DATABASE_NAME".
2. Click "Database Connection".
3. Go to "Download client credentials (Wallet) > Download Wallet".
   ![image-20240406175800888](C:\Users\marty\AppData\Roaming\Typora\typora-user-images\image-20240406175800888.png)
4. Type your password and Download.
5. Copy zipped file to a proper directory.
6. Open SQL Developer.
7. Open "File > New > General > Connections > Database Connection".
   ![image-20240406174206117](C:\Users\marty\AppData\Roaming\Typora\typora-user-images\image-20240406174206117.png)
8. Set Connection Name.
9. Type username and password.
10. Select connection type "Cloud Wallet".
11. Select downloaded wallet as Configuration File.
    ![image-20240406180058903](C:\Users\marty\AppData\Roaming\Typora\typora-user-images\image-20240406180058903.png)
12. Test.
13. Save.
14. Connect.

