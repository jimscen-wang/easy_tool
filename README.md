# easy_tool
Run easy_tool.exe

Select protocol.

Input the UDP/TCP payload as following.

/*payload heximal format*/

1122 

#BEGIN# -s #END# /*messesage seperator, one sent message*/

11 22

#BEGIN# -r #END# /*messesage seperator,one received message*/

11 22 /*payload heximal format*/

/*no messesage seperator is a sent msg*/

For example copy this to payload.

1122 

#BEGIN# -s #END#

11 22

#BEGIN# -r #END# 

11 22

Click save button to save as wiresharp file.
