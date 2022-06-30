# 5niff--1t
## Description
Do you think finding the flag is very easy?
## attachment
download the file from [here](https://traboda-arena-36.s3.amazonaws.com/files/attachments/file_1_a1f472bc-339b-48ce-a2f9-eca89a270cc9.logicdata?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA6GUFVMV6HO3NYL6Z%2F20220630%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Date=20220630T144650Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=5c7ab73d0a9183517c4f14fb8b61685d171fd1bb8afc8b67f4338febbaa433a6)
## hint
Analyzing stuffs are pretty interesting if we are using proper tools for it
## How I did it
So as the hint suggest I search for tools to analyse .logicdata file and found a tool called [saleae logic](https://support.saleae.com/logic-software/sw-download). I just analysed to file and saw that another hint was given to shift the baud rate to 12 times the present i.e from 9600 to 115200. now in the second channel I got the flag.

## Flag
This is the flag:ictf{part_of_a_balanced_breakfast}

