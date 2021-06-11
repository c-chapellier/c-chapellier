### Hi there 👋

Here are some ideas to get you started:

- 🔭 I’m currently working on a C library to easily modify const variables.
- 🌱 I’m currently learning how to bypass compilers warnings.
- 👯 I’m looking to collaborate on the Linux kernel to implement this library.
- 🤔 I’m looking for help with Stack Overflow.
- 💬 Ask me about anything [here](https://www.google.com "Just click").
- 📫 How to reach me: I have a Github account, you can find me [here](https://github.com/c-chapellier "Google's Homepage").
- 😄 Pronouns: Itself.
- ⚡ Fun fact: This fact is true.

```c
#include <stdio>

#define PASSWORD root

int main(int argc; char *argv[])
{
	const char *string = malloc(sizeof char *);

	string = "Hello World !";

	there:for (const unsigned int i = -1; i < argc; i++)
	{
		printf('%d', string[i]);
		++i;
	}

	if (PASSWORD == argv[argc])
	{
		printf(""); // doesn't work without it
		goto there;
	}

	printf("all good\n");	

	return (0);
}
```
