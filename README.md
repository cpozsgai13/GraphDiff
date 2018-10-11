# GraphDiff
Provide a diff tool for directed acyclic graphs

![Alt text](https://g.gravizo.com/svg?
digraph G {
rankdir=TB;
0[label=glossary,shape=component,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
1[label="title/ZamZam",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
2[label=GlossDiv,shape=component,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
3[label="title/S",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
4[label=GlossList,shape=component,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
5[label=GlossEntry,shape=component,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
6[label="ID/SGML",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
7[label="SortAs/SGML",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
8[label="GlossTerm/Standard Generalized Markup Language",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
9[label="Acronym/SGML",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
10[label="Abbrev/ISO 8879:1986",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
11[label=GlossDef,shape=component,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
12[label="para/A meta-markup language, used to create markup languages such as DocBook.",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
13[label=GlossSeeAlso,shape=box,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
14[label="GML/GML",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
15[label="XML/XML",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
16[label="GlossSee/markup",shape=ellipse,width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
0->1 ;
1->2 ;
0->2 ;
2->3 ;
3->4 ;
2->4 ;
4->5 ;
5->6 ;
5->7 ;
6->7 ;
5->8 ;
7->8 ;
5->9 ;
8->9 ;
5->10 ;
9->10 ;
10->11 ;
5->11 ;
11->12 ;
11->13 ;
12->13 ;
13->14 ;
13->15 ;
14->15 ;
5->16 ;
11->16 ;
{ rank=same 0}
{ rank=same 1,2}
{ rank=same 3,4}
{ rank=same 5}
{ rank=same 6,7,8,9,10,11,16}
{ rank=same 12,13}
{ rank=same 14,15}
}

)
