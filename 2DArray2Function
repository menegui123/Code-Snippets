#include <stdio.h>
#include <stdlib.h>

void DisplayPonteiro(int* Array, int Size);
void DisplayVetorDePonteiro(int (*Array)[2], int Size);


int Vector[2][2] = 
{
    {3, 4},
    {1, 2}
}; 

int main()
{
   // printf("Hello World");
    DisplayVetorDePonteiro(Vector, 2);
    DisplayPonteiro(Vector, 2);
    return 0;
}

void DisplayPonteiro(int *Ptr, int Size)
{
    int Len = sizeof(Ptr);
    int *Array = NULL;
    Array = Ptr;
    
    
    for(int i = 0; i < Size; i++)
    {
        for(int j = 0; j < 2; j++)
        {
            printf("%d", *((Array+i*Size) + j));
        }
    }
}

void DisplayVetorDePonteiro(int (*Array)[2], int Size)
{
        for(int i = 0; i < Size; i++)
    {
        for(int j = 0; j < 2; j++)
        {
            printf("%d", Array[i][j]);
        }
    }
}


