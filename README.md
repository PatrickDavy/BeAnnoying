# BeAnnoying
As the name states by running this command from bash  

for((i=0;i<1000;i++))do mkdir "Header Folder$i";cd "Header Folder$i"; for((j=0;j<100;j++))do mkdir "Sub Folder$j"; cd "Sub Folder$j"; echo "Text" > "txtfile.txt"; cd ..; done;  cd ..; done  
  
rm -r "Header Folder"*
