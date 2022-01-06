This is a basic playbook which was created by following every step from the below link:

https://thepi.io/how-to-use-your-raspberry-pi-as-a-wireless-access-point/


While testing on my ubuntu server i ahve to make some changes in the playbook, which are still there

The lines which i have commented ( which have # in front of them ) are the ones which i have modified or have used
different module for them. 

Line in file module ( which is commented from most places ) is used to add a line in a file which is already present at the path

Instead i have used Copy module which will create the file at the path and will add content to it.

To change this in your environment, uncomment ( remove # which is at the front of the line )

To use lineinfile module instead of copy module just remove # in front of lineinfile, line and add comment (#) in front of copy and content.

