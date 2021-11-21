
/**
 * @file funs.h
 * @author kswathi
 * @brief 
 * @version 0.1
 * @date 2021-11-21
 * 
 * @copyright Copyright (c) 2021
 * 
 */

#ifndef __FUNS_H__<br>
#define __FUNS_H__<br>
#include <stdio.h><br>
#include <string.h><br>

struct user.<br>
{<br>
    char name[30];<br>
    long int cnumber;<br>
    char ptype[20];<br>
    int ext;<br>
    char place[20];<br>
    char country[20];<br>
};<br>

struct user u;<br>

long int size;<br>

FILE *fptr, *ftemp;<br>

/**
 * @brief Displays all the properties available to buy.
 * 
 */<br>
void display_prop();<br>

/**
 * @brief User can view properties by type of the property
 * (villa, house, land).
 * 
 */
void display_type_prop();<br>

/**
 * @brief Sellers can add their properties so that they can be viewed 
 * by buyers.
 * 
 */
void add_prop();<br>

/**
 * @brief Sellers can remove their properties if like to
 * (incase sold out)
 * 
 */
void remove_prop();<br>

/**
 * @brief Sellers can change the specifications if they were entered 
 * wrong by mistake.
 * 
 */
void modify_prop();<br>

int display_number();<br>

#endif<br>










