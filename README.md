def print_line():
    print("+ - - - + - - - +")

def print_column():
    print("|       |       |")

def draw_grid():
    for i in range(2):
        print_line()
        for j in range(4):
            print_column()
    print_line()

draw_grid()
