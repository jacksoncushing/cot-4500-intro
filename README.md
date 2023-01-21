# cot-4500-intro
Intro Assignment for COT4500



if __name__ == '__main__':
    # matrix 1
    matrix = [[0, 0, 0], [0, 0, 0], [0, 0, 0]]
    i: int = 0
    for x in range(3):
        j: int = 0
        for y in range(3):
            if i == j:
                matrix[i][j] = 1
            else:
                matrix[i][j] = 0
            j = j + 1
        i = i + 1
    for x in range(3):
        for y in range(3):
            print(matrix[x][y], end=" ")
        print("\n")

    print("\n\n")

    # matrix 2

    for x in range(3):
        for y in range(3):
            if matrix[x][y] == 0:
                matrix[x][y] = 3
            else:
                continue

    for x in range(3):
        for y in range(3):
            print(matrix[x][y], end=" ")
        print("\n")

    print("\n\n")
    
    # matrix 3

    for x in range(3):
        for y in range(3):
            if y != 2:
                print(matrix[x][y], end=" ")
        print("\n")
