# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: okrifa <marvin@42.fr>                      +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2015/09/16 02:30:24 by okrifa            #+#    #+#              #
#    Updated: 2015/09/16 20:20:57 by okrifa           ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRCS_C = srcs/ft_putchar.c \
					srcs/ft_putstr.c \
					srcs/ft_strcmp.c \
					srcs/ft_strlen.c \
					srcs/ft_swap.c

SRCS_O =	ft_putchar.o \
					ft_putstr.o \
					ft_strcmp.o \
					ft_strlen.o \
					ft_swap.o

HEADER =	includes/

CC = gcc

CFLAGS = -Wall -Werror -Wextra

all: $(NAME)

$(NAME):
	$(CC) $(CFLAGS) -c $(SRCS_C) -I $(HEADER)
	ar rc $(NAME) $(SRCS_O)
	ranlib $(NAME)

clean:
	rm -rf $(SRCS_O)

fclean: clean
	rm -rf $(NAME)

re: fclean $(NAME)

