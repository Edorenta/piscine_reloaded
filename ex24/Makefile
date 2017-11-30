# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: pde-rent <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/09/19 16:48:47 by pde-rent          #+#    #+#              #
#    Updated: 2017/11/08 22:13:04 by pde-rent         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

LIB =		srcs/
INCLUDES =	includes
NAME = 		libft.a
HEADER =	libft.h

SRC =	$(LIB)ft_putchar.c		\
		$(LIB)ft_putstr.c		\
		$(LIB)ft_strcmp.c		\
		$(LIB)ft_strlen.c		\
		$(LIB)ft_swap.c

CMP =	ft_putchar.o		\
		ft_putstr.o		\
		ft_strcmp.o		\
		ft_strlen.o		\
		ft_swap.o

FLAGS = -Wall -Werror -Wextra

all: $(NAME)

$(NAME):	

	gcc $(FLAGS) -c $(SRC) -I ../$(INCLUDES)
	ar rc $(NAME) $(CMP)
	ranlib $(NAME)

clean:
	rm -rf $(CMP)

fclean: clean
	rm -rf $(NAME)

re: fclean all
