# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: pde-rent <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/09/19 16:48:47 by pde-rent          #+#    #+#              #
#    Updated: 2017/11/08 20:46:30 by pde-rent         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME =  ft_display_file
SRC =	source.c
CMP =	source.o
FLAGS = -Wall -Werror -Wextra

all: $(NAME)

$(NAME):
	gcc -c $(SRC)
	gcc $(CMP) -o $(NAME)

clean:
	/bin/rm -rf $(CMP)

fclean: clean
	/bin/rm -rf $(NAME)

re: fclean all
