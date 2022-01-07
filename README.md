
```var add2 = function(number) {
	return number + 2;
}```js

```is_x_gl:
        mov current_player, 1
        jmp game_loop

; Sets the correct attribute and prints the character
print_char PROC
                                                         
    mov AH, 09h ; Set interrupt to print
    mov CX, 1 ; So that the character is only printed once
    
    ; Set the correct attribute
    cmp AL, "X"
}```asm
