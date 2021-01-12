INFO

name: snake the game xD
author: n1kke
language: python 3.9
directory used: pygame, time, random, black
fonts used: Times New Roman
pep8: satisfied 

GETTING STARTED

to start game via folder: double-click on file 'main.py'
to start game via cmd: open folder using command 'cd the-path-of-the-folder', then use command 'python main.py'

A PIECE OF CODE:

# create player score
def Your_score(score):
    value = score_font.render("Your Score: " + str(score), True, yellow)
    dis.blit(value, [0, 0])

# create snake
def our_snake(snake_block, snake_list):
    for x in snake_list:
        pygame.draw.rect(dis, green, [x[0], x[1], snake_block, snake_block])