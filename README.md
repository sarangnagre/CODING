1).RESEARCH - 
                content       https://digitallibrary.mes.ac.in/server/api/core/bitstreams/2a67c5ae-dad9-4a08-a6be-9486f96673c2/content

It is a program based ON and OFF of a motar which we can use during farming (help farmers) so that irrigate crops.

2).ANALYSIS -                                                     
                      The purpose of automatic irrigation system is to reduce human intervention and still ensure proper irrigation. Agriculture is the main pillar of any economy because it plays very important role in the progress of a country. In the case of traditional irrigation system water saving is not considered and productivity of crops is also less. At present there is emerging global water crisis and threat of uncertain climatic conditions which adds to the problem of agricultural sector. In this project drip irrigation is used as it has potential to save water and nutrients as it places water directly into the root zone and minimizes evaporation.

1)avoid over-irrigation or under-irrigation of crops.
 2)To reduce labour & farming time. 
3) To minimize wastage of water.  
4)To control & maintain proper environmental conditions for crop.
            
   The automatic control system for irrigation system also achieves our aim of avoiding water loss. Due to continuous monitoring and quick response of system optimal crop quality and increase in farming efficiency is possible. 



3).IDEATE - 
                This hole program is to help farming industry to cope in this new era of technology. So that by using modern tools we can ease the labor,burden,human resource that are need if we use traditional irrigation method.The automatic control system for irrigation system also achieves our aim of avoiding water loss. Due to continuous monitoring and quick response of system optimal crop quality and increase farming efficiency.

4).BUILD-
Code
      #include <stdio.h>

int main() {
    int input_value;
    printf("welcome to Farming App.\n");
    printf("Follow Instructions to Use motar.\n");
    printf("Please press 0(to start)or 1(to stop):");
    scanf("%d", &input_value);

    if (input_value == 0) {
        printf("status:Motar ON.\n");
    } else if (input_value == 1) {
        printf("status:Motar OFF.\n");
    } else {
        printf("status: INVALID INPUT.\nPlease Enter 0(to start)or1(to stop)\n");
    }

    return 0;
}          
   
Output- 
                     Welcome to Farming App.
                             Follow Instructions to Use motar.
                             Please press 5(to start)or 9(to stop):
                             
 
 

5).TEST- 
            i) welcome to Farming App.
                           Follow Instructions to Use motar.
                           Please press 5(to start)or 9(to stop):5
                            status:Motar ON.

                        ii) welcome to Farming App.
                         Follow Instructions to Use motar.
                         Please press 5(to start)or 9(to stop):9
                         status:Motar OFF.
        
                        iii) welcome to Farming App.
                         Follow Instructions to Use motar.
                         Please press 5(to start)or 9(to stop):8
                         status: INVALID INPUT.
                        Please Enter 5(to start)or9(to stop)

