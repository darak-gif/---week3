# ---week3
homework
//зад 6 Напишете програма, която, по дадено число а и степенен показател n, намира а нa n-та степен.
    
    int number, powOfNumber, newNumber;
    std::cout << "Enter the number : ";
    std::cin >> number;
    std::cout << "Enter the pow : ";
    std::cin >> powOfNumber;
    newNumber = number;
    for (int i = 1; i < powOfNumber; i++) {
        newNumber*=number;
    }
    std::cout << "The result is = " <<newNumber;
