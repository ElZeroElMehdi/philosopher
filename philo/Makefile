# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: eelmoham <eelmoham@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/06/17 10:15:28 by eelmoham          #+#    #+#              #
#    Updated: 2022/06/17 10:15:29 by eelmoham         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = philo
CC = gcc
RM = rm -f
CFLAGS=	-Wall -Wextra -Werror

HEADER= philosopher.h

SRCM = ./main.c\
		./exec.c\
		./list.c\
		./utils.c\
		./parsing/valid_args.c\
		./parsing/valid_time.c

$(NAME) : $(SRCM) $(HEADER)
	$(CC) $(CFLAGS) $(SRCM) -o $(NAME)

all : $(NAME)

clean:
	$(RM) philo
fclean: clean	

re : fclean all

.PHONY: fclean clean all
