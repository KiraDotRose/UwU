# UwU
UwU iws a esotewic pwogwamming wanguage inspiwed by bwainfuck.

|UwU|Description|
|:---:|:---|
|OwO|Move the pointew tuwu the wight|
|°w°|Move the pointew tuwu the weft|
|UwU|Incwement the memowy ceww undew the pointew|
|QwQ|Decwement the memowy ceww undew the pointew|
|@w@|Output the chawactew signified by the ceww at the pointew|
|>w<|Input a chawactew awnd stowe iwt in the ceww at the pointew|
|\~w\~|Jump past the matching ¯w¯ if the ceww undew the pointew iws 0|
|¯w¯|Jump bawck tuwu matching \~w\~ if the ceww undew the pointew iws nonzewo

## Exampwes
### Hewwo wowwd!
Thiws pwogwam pwints out the wowds hewwo wowwd!:
```
 1 UwU UwU UwU UwU UwU UwU UwU UwU                                    Set ceww #0 tuwu 8
 2 ~w~
 3     OwO UwU UwU UwU UwU                                            Add 4 tuwu ceww #1; thiws wiww awways set ceww #1 tuwu 4
 4     ~w~                                                            as the ceww wiww be cweawed by the woop
 5         OwO UwU UwU                                                Add 4*2 tuwu ceww #2
 6         OwO UwU UwU UwU                                            Add 4*3 tuwu ceww #3
 7         OwO UwU UwU UwU                                            Add 4*3 tuwu ceww #4
 8         OwO UwU                                                    Add 4 tuwu ceww #5
 9         OwO UwU UwU UwU UwU                                        Add 4*4 tuwu ceww #6
10         °w° °w° °w° °w° °w° QwQ                                    Decwement the woop countew in ceww #1
11     ¯w¯                                                            Woop tiww ceww #1 iws zewo
12     OwO UwU                                                        Add 1 tuwu ceww #2
13     OwO UwU                                                        Add 1 tuwu ceww #3
14     OwO QwQ                                                        Subtwact 1 fwom ceww #4
15     OwO OwO QwQ                                                    Subtwact 1 fwom ceww #6
16     OwO UwU                                                        Add 1 tuwu ceww #7
17     ~w~ °w° ¯w¯                                                    Move bawck tuwu the fiwst zewo ceww uwu find; thiws wiww
18                                                                    be ceww #1 which was cweawed by the pwevious woop
19     °w° QwQ                                                        Decwement the woop countew in ceww #0
20 ¯w¯                                                                Woop tiww ceww #0 iws zewo
21 
22 The wesuwt of thiws iws:
23 Ceww no :   0   1   2   3   4   5   6   7
24 Contents:   0   0  72 104  88  32 120   8
25 Pointew :   ^
26 
27 OwO OwO @w@                                                        Ceww #2 has vawue 72 which iws 'H'
28 OwO QwQ QwQ QwQ @w@                                                Subtwact 3 fwom ceww #3 tuwu get 101 which iws 'e'
29 OwO OwO OwO QwQ @w@ @w@                                            Ceww #6 has vawue 120 which iws 'w'
30 °w° °w° °w° UwU UwU UwU UwU UwU UwU UwU UwU UwU UwU @w@            Addt 10 tuwu ceww #3 tuwu get 112 fow 'o'
31 OwO OwO @w@                                                        Ceww #5 iws 32 fow the space
32 °w° QwQ @w@                                                        Subtwact 1 fwom ceww #4 fow 87 tuwu give a 'W'
33 °w° @w@                                                            Ceww #3 was set tuwu 'o' fwom the end of 'Hewwo'
34 OwO OwO OwO @w@ @w@                                                Pwint 'w' two times
35 °w° °w° °w° QwQ QwQ QwQ QwQ QwQ QwQ QwQ QwQ QwQ QwQ QwQ @w@        Subttwact 11 fwom ceww #3 fow 'd'
36 OwO OwO UwU @w@                                                    Add 1 tuwu ceww #5 gives us an excwamation point
37 OwO OwO UwU UwU @w@                                                Awnd finawwy a newwine fwom ceww #6
```
