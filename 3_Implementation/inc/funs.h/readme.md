
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

#ifndef __FUNS_H__.<br>
#define __FUNS_H__.<br>
#include <stdio.h>.<br>
#include <string.h><br>

struct user.<br>
{
    char name[30];<br>
    long int cnumber;<br>
    char ptype[20];<br>
    int ext;
    char place[20];
    char country[20];
};

struct user u;

long int size;

FILE *fptr, *ftemp;

/**
 * @brief Displays all the properties available to buy.
 * 
 */
void display_prop();

/**
 * @brief User can view properties by type of the property
 * (villa, house, land).
 * 
 */
void display_type_prop();

/**
 * @brief Sellers can add their properties so that they can be viewed 
 * by buyers.
 * 
 */
void add_prop();

/**
 * @brief Sellers can remove their properties if like to
 * (incase sold out)
 * 
 */
void remove_prop();

/**
 * @brief Sellers can change the specifications if they were entered 
 * wrong by mistake.
 * 
 */
void modify_prop();

int display_number();

#endif










