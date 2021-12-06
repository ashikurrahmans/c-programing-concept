<h1 align="center">Problem solving through c language</h1>

<h3>Table of contents </h3>

| No | Questions | 
| --- | --- |
|| **Input & Output System** | 
| 1 | [Make Lower case to Capital](#make-lower-case-to-capital) | 
| 2 | [Make Capital case to Lower](#make-capital-case-to-lower)|
| 3 | [Convert Decimal to Hexa Decimal](#decimal-to-hexa-decimal)|
| 4 | [Sum 2 numbers from inputs](#sum-2-numbers-from-inputs)|
| 5 | [Average number from inputs](#average-number-from-inputs)|
| 6 | [Area of a triangle by height & weight](#area-of-a-triangle-from-inputs)|
| 7 | [Length of 3 sides of triangle](Length-of-3-sides-of-a-triangle ) | 




1. ###  Make lower case to capital
```
    char makeCapital;
    printf("Write a lower case character : ");
    scanf("%c",&makeCapital);
    printf("Your conversion is : %c",makeCapital - 32;
 ```   
    
    
2. ### Make Capital case to Lower 
```
    char makeLower;
    printf("Write a Capital character : ");
    scanf("%c",&makeLower);
    printf("Your conversion is : %c",makeLower + 32);
```    

3. ### Decimal to Hexa Decimal 
```
    int number;
    printf("Write an integer number : ");
    scanf("%d",&number);

    printf("Hexadecimal Number : %x",number);
```



4. ### Sum 2 Numbers from inputs 
    in this section i am going to take 2 different numbers for make addition ans show the result in console.  
```

    int num1,num2,sum;
    printf("Write two numbers : ");
    scanf("%d %d",&num1,&num2);

    sum = num1 + num2;
    printf("Two number sum is : %d",sum);

```

5. ### Average Number from inputs 

```
    int num1,num2,result;
    float evg;
    printf("Write two numbers :");
    scanf("%d %d",&num1,&num2);

    result = num1 + num2 ;
    printf("Sum is : %d", result);

    evg = (float)result / 2 ;
    printf("average is : %.1f",evg);
```
    
6. ### Area Of A Triangle from inputs 

```
    float height , base , area;
    printf("What is your height : ");
    scanf("%f",&height);
    printf("What is your width : ");
    scanf("%f",&base);
    area = (float)1/2 * height * base;
    printf("Result is : %.2f",area);
```

7. ### Length of 3 sides of a triangle 


```
    double a , b , c, s , area;
    printf("Enter 3 Values : ");
    scanf("%lf %lf %lf",&a,&b,&c);

    s = (a+b+c)/2;
    area = sqrt(s*(s-a)*(s-b)*(s-c));

    printf("The Area of Triangle : %.2lf",area);
```

