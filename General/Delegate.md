Delegate

Delegate - переменная хранящая ссылку на метод

```c#
public delegate int myDel(int number);
public class Program
{
public int AddNumbers(int a)
{
int Sum = a + 10;
return Sum;
}
public void Start()
{
myDel DelgateExample = AddNumbers;
}
}
```

