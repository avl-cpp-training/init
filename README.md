#### inicijalni test (jezik C)

Što ispisuju sljedeći programi?

**1.**
```
int main(){
	int n;
	printf("%d", n);
}
```

1. 0
2. -1
3. slučajni sadržaj memorijske lokacije
4. ovisi o postavkama projekta

Odgovor: 3

**2.**
```
int n;
int main(){
	printf("%d", n);
}
```

1. 0
2. -1
3. slučajni sadržaj memorijske lokacije
4. ovisi o postavkama projekta

Odgovor: 1

**3.** 
```
int main(){
	int n = -1;
	printf("%u", n);
}
```
1. 0
2. -1
3. 4294967295
4. ovisi o postavkama projekta

Odgovor: 3

**4.**
```
void f(int a, int b){
	a = b; b = a;
}

int main(){
	int a = 1, b = 2;
	f(a, b);
	printf("%d %d", a, b);
}
```
1. 1 1
2. 1 2
3. 2 1
4. 2 2

Odgovor: 2

**5.** 
```
struct s{
	long a;
	char b;
};

int main(){
	printf("%d", sizeof(struct s));
}
```
1. 4
2. 5
3. 8
4. ovisi o postavkama projekta

Odgovor: 3
