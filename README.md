# Ugur--Can--Karakelle
Computer 
#include <stdio.h>

int main() {
    printf("Merhaba, ben C programıyım.\n");
    printf("Seninle biraz kodlama yapmak hoş olacak!\n");
    printf("Ama şimdiye kadar bana verdiğin tüm tuhaf girdilerden bahsetmek zorundayım...\n");

    char input[100];
    printf("Seninle ilgili en tuhaf şey nedir?: ");
    scanf("%s", input);
    printf("Bunu not ettim: %s\n", input);

    printf("Şimdi başka bir sorum var: İdeal bir dünya nasıl olurdu?: ");
    scanf("%s", input);
    printf("Hmm, anlaşıldı: %s. Senin hayallerinin peşinden gitmeye devam et!\n", input);

    return 0;
}