<h1 align="center">Operators Practice</h1>

[1 : Sum 2 Numbers](#sum-2-numbers)</br>
[2 : Average number](#average-numbers)</br>
[3 : Area of a triangle](#areaofatriangle)</br>






### 1 : Sum 2 Numbers 

```

    int num1,num2,sum;
    printf("Write two numbers : ");
    scanf("%d %d",&num1,&num2);

    sum = num1 + num2;
    printf("Two number sum is : %d",sum);

```

### 2 : Average Numbers

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
    
### 3 : Area of A Triangle

```
    float height , base , area;
    printf("What is your height : ");
    scanf("%f",&height);
    printf("What is your width : ");
    scanf("%f",&base);
    area = (float)1/2 * height * base;
    printf("Result is : %.2f",area);
```
