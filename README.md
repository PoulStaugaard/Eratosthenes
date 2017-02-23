}# Eratosthenes
var n = args[0]
var bits = new bit[n];
var sqn = sqrt(n);
for (i=2; i < n; i++)
{
  if (bits[i])
  {
    Console.WriteLine(i);
  }
  for (j=i*2; j < sqn; j+=i)
  {
    bits[n] = false;
  }
}
