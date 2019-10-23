********************************************************************************
                                                                                
                                                          :::      ::::::::     
     README.md                                          :+:      :+:    :+:     
                                                      +:+ +:+         +:+       
     By: abourin <marvin@42.fr>                     +#+  +:+       +#+          
                                                  +#+#+#+#+#+   +#+             
     Created: 2019/10/23 20:29:39 by abourin           #+#    #+#               
     Updated: 2019/10/23 20:38:23 by abourin          ###   ########.fr         
                                                                                
********************************************************************************

## Run tests with your printf library

1. Compile your printf library
2. Place `libftprintf.a` output in repository directory.
3. Run test.sh

Wait until printf tester compile default `main.c` with real printf and compared it
to your printf library. 

This tester test all cases about these conversion specifiers : 

- %%
- %s
- %c
- %p
- %d
- %i
- %u
- %x
- %X

And these bonus :

- %f (for float)
- %n (to write chars count inside)

With all of these printf's flags :

-0.*

Feel free to fork this repository and add potential tests forgotten here.