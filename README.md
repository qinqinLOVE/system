int IsChongfu(PNode List,int val){
PNode P = List -> Next;
if (P == NULL){
        printf("链表为空");
        }
        while(P!=NULL){
         if(P->Element==val){
         printf("\n有重复！\n\n");
return 0;
break;
}
P=P->Next;
}
return 1; 
}
