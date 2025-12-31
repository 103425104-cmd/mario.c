def main():
    while True:
        try:
            n = int(input("Height: "))
            if 1 <= n <= 8:
                break
        except ValueError:
            continue

    for i in range(1, n + 1):
        print(" " * (n - i) + "#" * i)


if __name__ == "__main__":
    main()
Height: 5
    #
   ##
  ###
 ####
#####
