# Libft

*This project has been created as part of the 42 curriculum by <agaleksa>.*

*Այս նախագիծը ստեղծվել է 42-ի ուսումնական ծրագրի շրջանակում <agaleksa>-ի կողմից։*

---

## Description / Նկարագրություն

Libft is a personal C library that reimplements a set of standard libc functions, additional useful functions, and linked list operations.  
It helps understand how standard C functions work under the hood and allows you to use your own library in future assignments.

**Armenian / Հայերեն**  
Libft-ը C լեզվով գրանցված անձնական գրադարան է, որը վերակենդանացնում է որոշ ստանդարտ libc ֆունկցիաներ, ինչպես նաև ավելացնում է օգտակար ֆունկցիաներ և կապված ցուցակների գործառույթներ։  
Այս նախագիծը օգնում է հասկանալ, թե ինչպես են աշխատում հիմնական C ֆունկցիաները և թույլ է տալիս դրանք օգտագործել ապագա առաջադրանքներում։

---

## Project Goal / Նախագծի նպատակ

- Reimplement libc functions with the `ft_` prefix.  
- Create useful string, memory, and linked list manipulation functions.  
- Understand memory allocation, pointers, and linked list operations.  

**Armenian / Հայերեն**  
- Վերակենդանացնել libc ֆունկցիաները `ft_` հավելվածով:  
- Ստեղծել օգտակար ֆունկցիաներ շղթայական ցուցակների, բեռնման և հուշող ֆունկցիաների համար:  
- Հասկացնել հիշողության բաշխումը, ցուցիչները և կապված ցուցակների գործառույթները:

---

## Tasks Completed / Արտադրված աշխատանքներ

---

Part 1 – Libc Functions / Մաս 1 – libc ֆունկցիաներ

 ft_isalpha — check if character is a letter / ստուգում է, թե արդյոք նիշը տառ է

 ft_isdigit — check if character is a digit / ստուգում է, թե արդյոք նիշը թիվ է

 ft_isalnum — check if character is alphanumeric / ստուգում է, թե նիշը տառ կամ թիվ է

 ft_isascii — check if character is ASCII / ստուգում է, թե նիշը ASCII է

 ft_isprint — check if character is printable / ստուգում է, թե նիշը տպելի է

 ft_strlen — get length of string / ստանում է տողի երկարությունը

 ft_memset — fill memory with a byte / հիշողությունը լցնում է նշված բայթով

 ft_bzero — zero out memory / հիշողությունը զրոյացնում է

 ft_memcpy — copy memory / պատճենում է հիշողությունը

 ft_memmove — safely copy memory / անվտանգ պատճենում է հիշողությունը

 ft_strlcpy — copy string with size limit / պատճենում է տողը սահմանված չափով

 ft_strlcat — concatenate strings with size limit / միացնում է տողերը սահմանված չափով

 ft_toupper — convert char to uppercase / նիշը վերածում է մեծատառի

 ft_tolower — convert char to lowercase / նիշը վերածում է փոքրատառի

 ft_strchr — find character in string / գտնում է նիշը տողում

 ft_strrchr — find last occurrence of character / գտնում է վերջին հանդիպումը

 ft_strncmp — compare strings up to n characters / համեմատում է տողերը մինչև n նիշ

 ft_memchr — locate byte in memory / գտնում է բայթը հիշողության մեջ

 ft_memcmp — compare memory blocks / համեմատում է հիշողության բլոկները

 ft_strnstr — locate substring with length limit / գտնում է ենթատողը սահմանված երկարությամբ

 ft_atoi — convert string to integer / տողը վերածում է ամբողջ թվի

 ft_calloc — allocate and zero memory / հատկացնում և զրոյացնում է հիշողությունը

 ft_strdup — duplicate string / պատճենում է տողը

---

Part 2 – Additional Functions / Մաս 2 – լրացուցիչ ֆունկցիաներ

 ft_substr — create substring / ստեղծում է ենթատող

 ft_strjoin — join two strings / միացնում է երկու տող

 ft_strtrim — trim characters from string / հանում է նիշերը տողից սկզբից և վերջից

 ft_split — split string by delimiter / բաժանում է տողը սահմանիչ նիշի վրա

 ft_itoa — convert integer to string / ամբողջ թիվը վերածում է տողի

 ft_strmapi — apply function to each char, return new string / կիրառել ֆունկցիան յուրաքանչյուր նիշի վրա, վերադարձնում է նոր տող

 ft_striteri — apply function to each char in place / կիրառել ֆունկցիան յուրաքանչյուր նիշի վրա՝ փոփոխելով սկզբնական տողը

 ft_putchar_fd — output character to file descriptor / տպել նիշը ֆայլի բնութագրիչին

 ft_putstr_fd — output string to file descriptor / տպել տողը ֆայլի բնութագրիչին

 ft_putendl_fd — output string with newline / տպել տողը նոր տողի հետ

 ft_putnbr_fd — output integer to file descriptor / տպել ամբողջ թիվը ֆայլի բնութագրիչին

---

Part 3 – Linked List / Մաս 3 – կապակցված ցուցակ

 ft_lstnew — create new node / ստեղծել նոր հանգույց

 ft_lstadd_front — add node at the beginning / ավելացնել հանգույցը ցուցակի սկզբին

 ft_lstsize — get list size / ստանալ ցուցակի չափը

 ft_lstlast — get last node / ստանալ վերջին հանգույցը

 ft_lstadd_back — add node at the end / ավելացնել հանգույցը ցուցակի վերջում

 ft_lstdelone — delete single node / ջնջել մեկ հանգույց

 ft_lstclear — delete entire list / ջնջել ամբողջ ցուցակը

 ft_lstiter — apply function to each node / կիրառել ֆունկցիան յուրաքանչյուր հանգույցի վրա

 ft_lstmap — create new list from function / ստեղծել նոր ցուցակ ֆունկցիայի հիման վրա
