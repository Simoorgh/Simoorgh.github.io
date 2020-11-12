---
published: true
---
## A New Post about source code in MD file


Meoooooooooow!


![Merlin](http://saiepour.co.uk/merlin.jpg)




Ruby Code:


  def find_missing(sequence)
    consecutive     = sequence.each_cons(2)
    differences     = consecutive.map { |a,b| b - a }
    sequence        = differences.max_by { |n| differences.count(n) }
    missing_between = consecutive.find { |a,b| (b - a) != sequence }
    missing_between.first + sequence
  end


C# code:


  // Copyright (c) Microsoft Corporation. All rights reserved.
  // Licensed under the MIT License.

  using Microsoft.AspNetCore.Hosting;
  using Microsoft.Extensions.Hosting;

  namespace TodoListService
  {
      public class Program
      {
          public static void Main(string[] args)
          {
              CreateHostBuilder(args).Build().Run();
          }

          public static IHostBuilder CreateHostBuilder(string[] args) =>
              Host.CreateDefaultBuilder(args)
                  .ConfigureWebHostDefaults(webBuilder =>
                  {
                      webBuilder.UseStartup<Startup>();
                  });
      }
  }


Good luck!
