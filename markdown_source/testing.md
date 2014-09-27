<!-- How to use comments in these files -->
<!-- ---------------------------------- -->
<!--
## This is just an idea at the moment, however this may be a good way to create common worksheets which are adaptable for everyone! ## 

Comments have been put in this file so that they can be customised for a range of workshops and uses.

The convention will be to create a TAG for your purpose and add this to the top of the file with a description.  ## More details will be added when I've experimented further with this concept ##

You can then add comments around any specific sections you need for your workshop and allow others to use the same setups (i.e. if you change to using different hardware you can have alternative sections which describe using that hardware instead of the Pi-Stop).

Once established, we can switch between setups by using a Python Script to generate specific PDFs based on the selected TAGS.

## This is just an idea at the moment, however this may be a good way to create common worksheets which are adaptable for everyone! ## 
-->
#Testing with defines#

<!---#define WANT_MODEL_PLUS--->
<!--Commented out define WANT_MODEL_ORG-->

#Testing with WANT_ONLINE_IMG_PATH#
<!---#define WANT_ONLINE_IMG_PATH--->

<!---
#ifdef WANT_ONLINE_IMG_PATH
<img src="https://raw.githubusercontent.com/PiHw/Pi-Stop/master/markdown_source/img/pihwlogotm.png" height=200 />
#else
--->
<img src="img/PiStopLocationsPlus.png" height=200 />
<!---#endif--->

#Testing with ONLINE_IMG_PATH#
<!---#define ONLINE_IMG_PATH https://raw.githubusercontent.com/PiHw/Pi-Stop/master/markdown_source--->
<!---
#ifdef WANT_ONLINE_IMG_PATH
<img src="ONLINE_IMG_PATH/img/PiStopLocationsPlus.png" height=200 />
#else
--->
<img src="img/PiStopLocationsPlus.png" height=200 />
<!---#endif--->


#Testing with IMG_PATH#

<!---
#define ONLINE_IMG_PATH https://raw.githubusercontent.com/PiHw/Pi-Stop/master/markdown_source/img
#define LOCAL_IMG_PATH img
--->

<!---
#ifdef WANT_ONLINE_IMG_PATH
#define IMG_PATH ONLINE_IMG_PATH
#else
#define IMG_PATH LOCAL_IMG_PATH
#endif
--->

<!---
#ifdef IMG_PATH
<img src="IMG_PATH/PiStopLocationsPlus.png" height=200 />
#else
--->
<img src="img/PiStopLocationsPlus.png" height=200 />
<!---#endif--->

<!---#ifdef WANT_MODEL_PLUS--->
##GPIO Connections for Model A+ and B+##
<img src="img/GPIOConnections01Plus.png" height=200 />
<img src="img/GPIOConnections02Plus.png" height=200 />
<!---#endif--->



<!---#ifdef WANT_MODEL_ORG--->
##GPIO Connections for Model A and B##
<img src="img/GPIOConnections01.png" height=200 />
<img src="img/GPIOConnections02.png" height=200 />
<!---#endif--->