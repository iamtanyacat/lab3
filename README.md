# lab3
Vysotin Ilya, Kosheleva Tanya AT-93
--------------------------------------------------------------
                                                             |
Winter Morning                                               |
                                                             |
Hard frost and sunshine – a day of pleasure!                 |
You are still drowsy at your leisure –                       |
It’s time, my beauty, ope your eyes!                         |
Let you get free of blissful dreaming,                       |
To meet the North Aurora, deeming                            |
The Star of North, let you arise!                            |
                                                             |
--------------------------------------------------------------
А.С. Пушкина писал: "Под старость жизнь такая гадость...".   |
--------------------------------------------------------------

d = {}
for c in (65, 97):
    for i in range(26):
        d[chr(i+c)] = chr((i+13) % 26 + c)

print("".join([d.get(c, c) for c in s]))
