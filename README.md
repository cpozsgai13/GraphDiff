# GraphDiff
Provide a diff tool for directed acyclic graphs

![Alt text](https://g.gravizo.com/svg?
digraph G {
rankdir=TB;
0[shape=record style=filled label=Header,width=1,height=1,fillcolor="#00ef007f",color=black,style=filled];
1[shape=record style=filled label="{Company|{IBM}}",width=1,height=1,fillcolor="#00ef007f",color=black,style=filled];
2[shape=record style=filled label=Prices,width=1,height=1,fillcolor="#00ef007f",color=black,style=filled];
3[shape=record style=filled label="{Last|{140.1}}",width=1,height=1,fillcolor="#00ef007f",color=black,style=filled];
4[shape=record style=filled label="{High|{146.81}}",width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
5[shape=record style=filled label="{Lo|{134.7}}",width=1,height=1,fillcolor="#0000ee5f",color=black,style=filled];
6[shape=record style=filled label="{High|{147.81}}",width=1,height=1,fillcolor="#fe00005f",color=black,style=filled];
7[shape=record style=filled label="{Lo|{134.1}}",width=1,height=1,fillcolor="#fe00005f",color=black,style=filled];
0->1 ;
1->2 ;
0->2 ;
2->3 ;
2->4 ;
3->4 ;
2->5 ;
4->5 ;
2->6 ;
3->6 ;
2->7 ;
{ rank=same 6,7}
{ rank=same 0,1}
{ rank=same 2,3,4}
}
)
