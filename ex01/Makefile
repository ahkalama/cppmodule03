SRC = main.cpp ClapTrap.cpp ScavTrap.cpp
OBJ = $(SRC:.cpp=.o)
CC = c++
RM = rm -f
CPPFLAGS = -Wall -Wextra -Werror -std=c++98

NAME = ScavTrap

all: $(NAME)

$(NAME): $(OBJ)
	@$(CC) $(CPPFLAGS) $(OBJ) -o $(NAME)
	@echo "\033[0;32mDone\033[m"

clean:
	@$(RM) $(OBJ)
	@echo "\033[0;34mclean\033[m"

fclean: clean
	@$(RM) $(NAME)
	@echo "\033[0;36mfclean\033[m"
	
re: fclean $(NAME)

.PHONY: all clean fclean re