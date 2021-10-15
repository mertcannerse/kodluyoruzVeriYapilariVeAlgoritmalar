## Merge Sort Projesi&nbsp;

**[16,21,11,8,12,22]** -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

​ &nbsp;&nbsp;&nbsp; [16,21,11,8,12,22]

​ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \

​ &nbsp;&nbsp; [16,21,11] &nbsp;&nbsp;&nbsp; [8,12,22]

​ &nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \

 &nbsp; [16] &nbsp; [21,11] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,12] &nbsp; [22]

​&nbsp;&nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp; \

&nbsp; [16] &nbsp; [21] &nbsp; [11] &nbsp; [8] &nbsp; [12] &nbsp; [22]

​&nbsp;&nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp; / &nbsp;&nbsp;&nbsp;&nbsp; /

&nbsp;&nbsp;&nbsp; [16] &nbsp; [11,21] &nbsp;&nbsp;&nbsp;&nbsp; [8,12] &nbsp; [22]

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [11,16,21] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,12,22]

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; \ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /

​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [8,11,12,16,21,22]



2. Big-O gösterimini yazınız.
   - O(nlogn)

