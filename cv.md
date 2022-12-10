# Pavel Zalenski
![foto](2022-12-09_11-06-27.png)

---
### Contacts

* Location: Kalinkovichi, Belarus
* Phone: +375 29 210-39-24
* Email: zalenpo@gmail.com
* GitHub: [ZalenchP](https://github.com/ZalenchP/rsschool-cv)
* Discord: zalench#4775

---
### About Me

My goal at the moment is to realize myself as a professional pragrammer. My strengths: Sharp mind. A bore in matters of interest to me. Curiosity. Resourcefulness in finding solutions to problems. Worked as an individual entrepreneur (retail trade). At the moment I work as a crusher operator (plastic processing). The desire to be the best in my field motivates me to develop myself.

---
### Skills

* C#(Basic)

---
### Code Example

[codewars.com](https://www.codewars.com/kata/523f5d21c841566fde000009/train/csharp) 
```
public class Kata { public static int[] ArrayDiff(int[] a, int[] b)
{ 
int lengthNewArray = a.Length; // the length of the future arrayab, which I will decriminate


for (int i = 0; i < a.Length; i++)       //find out the length of the future array

{
    for (int j = 0; j < b.Length; j++)
    {
        if (a[i] == b[j])
        {
            lengthNewArray--;
            break;
        }
    }
}

int[] c = new int[lengthNewArray];   //initialize future array

int indexC = 0;                       //future array index


for (int i = 0; i < a.Length; i++)      
{
    int count = 0;
    for (int j = 0; j < b.Length; j++)
    {
        if (a[i] == b[j])
        {
            count++;                 //check for repetitions

        }
    }
    if (count == 0)                 //if there were no repetitions, then I include this element in a new array
    {
        c[indexC] = a[i];
        indexC++;
    }
}

return c;
}
} 
```
---
### Experience
No programming experience.

---
### Education
Belarus. Kalinkovichi. Agricultural College. Agronomist.

---
### Courses 
.NET Development (2021Q4/BY/2) completed course.

---
### English
English level A1 

---
### Projects
No completed projects yet. https://github.com/ZalenchP/rsschool-cv
