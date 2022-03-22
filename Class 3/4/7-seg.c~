#include <mega32.h>
#include <delay.h>
void main(void)
{
DDRA = 0xFF;
DDRB = 0xFF;
while (1) {
PORTA= 0b00000001;
PORTB= 0b11111111;
delay_ms(100);
PORTA= 0b00000001;
PORTB= 0b11111111;
delay_ms(100);
}
}