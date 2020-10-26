/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>
#define TRUE 1
#define FALSE 0

#define Exit 1
#define AddItem 2
#define DeleteItem 3
#define ListItems 4
#define Sale 5
#define Stock 6
#define NetWorth 7

void Display_Menu () {
    printf ("The Menue\n");
    printf ("1 --- Exit\n");
    printf ("2 --- Add an Item to the store\n");
    printf ("3 --- Delete an Item from the store\n");
    printf ("4 --- List the items\n");
    printf ("5 --- sale an item\n");
    printf ("6 --- Add the stoce to the store\n");
    printf ("7 --- Net worth of the store\n");
}

int Get_Command () {
    int Command;
    
    printf ("Tell me what to do - type the number associated the function -- ");
    scanf ("%d", &Command);
 //   while (getchar() != '\n');
    return Command;
}

void Add_Item () {
    printf ("Item Added\n");
}

void List_Items () {
    printf ("Listed the Items\n");
}

void Delete_Item () {
    printf ("Item is deleted\n");
}

void Sale_Item () {
    printf ("Item has been sold\n");
}

void Add_Stock() {
    printf ("Stock has been added\n");
}
void Show_NetWorth () {
    printf ("The net worth of the store is zero\n");
}

int Execute_Command (int Command) {
    switch (Command) {
        case Exit : return (FALSE);
        case AddItem : Add_Item (); break;
        case ListItems : List_Items (); break;
        case DeleteItem : Delete_Item (); break;
        case Sale : Sale_Item (); break;
        case Stock : Add_Stock (); break;
        case NetWorth : Show_NetWorth (); break;
        default : printf ("I do not know how to execute this comman %d\n", Command);
    }
    
    printf ("The command %d is executed successfully\n", Command);
    return (TRUE);    
}

int main()
{
    
    while (TRUE) {
        Display_Menu ();
        if (!Execute_Command(Get_Command())) break;
    }
    printf ("Program ends here\n");
    return 0;
}
