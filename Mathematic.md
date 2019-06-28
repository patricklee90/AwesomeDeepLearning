# Mathematic

Mathematic is the essential component when dealing with deep learning, so it is necessary to understand the mathematic component and apply the theory into application


## Least Common Multiple(LCM)
[LCM introduction](https://www.youtube.com/watch?v=vmMAKkEWTAI), by MathSmart, Youtube
[LCM](https://en.wikipedia.org/wiki/Least_common_multiple), by Wikipedia
- smallest common multiple of two integers a and b, usually denoted by LCM(a, b), is the smallest positive integer that is divisible by both a and b.
- that can be used before fractions can be added, subtracted or compared. 
- The LCM of more than two integers is also well-defined: it is the smallest positive integer that is divisible by each of them.

'''C#
{
  public static int getTotalX(List<int> a, List<int> b)
    {
        List<int> consideredInt = new List<int>();

        //Get a List containing all int in range of input
        for(int i = 1; i <=100; i++) { consideredInt.Add(i); }

        //check condition 1
        for(int i = 0; i < a.Count; i++)
        {
            for(int j = 0; j < consideredInt.Count; j++)
            {
                if (consideredInt[j] % a[i] != 0)
                {
                    consideredInt.RemoveAt(j);
                    j--;
                }
            }
        }
    }
    }
'''

## Greatest Common Divisor(DCM)
- which are not all zero, is the largest positive integer that divides each of the integers.
- The greatest common divisor is also known as the greatest common factor (gcf),[3] highest common factor (hcf),[4] greatest common measure (gcm),[5] or highest common divisor.[6]
