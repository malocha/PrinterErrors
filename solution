using System;
using System.Text.RegularExpressions;

public class Printer 
{
    public static string PrinterError(String s) 
    {
      int n = 0;
      Regex mz = new Regex(@"[n-z]");
      var matches = mz.Matches(s);
      foreach (Match match in matches) {
        n += 1;
      }
      return (n.ToString() + "/" + (s.Length).ToString());
    }
}
