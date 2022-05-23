SRC		=	ft_printf.c ft_utils.c ft_print_uint.c ft_print_ptr.c ft_print_hexa.c ft_print_nbr.c ft_print_str.c ft_print_percent.c

OBJ		=	$(SRC:.c=.o)

CC		=	gcc
RM		=	rm -f
CFLAGS	=	-Wall -Werror -Wextra

NAME	=	libftprintf.a

all:		$(NAME)

$(NAME):	$(OBJ)
			ar rcs $(NAME) $(OBJ)

clean:
			$(RM) $(OBJ)

fclean:		clean
			$(RM) $(NAME)

re:			fclean $(NAME)

.PHONY:		all clean fclean re
