- 👋 Hi, I’m @Duckhubhack
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...


<!---
Duckhubhack/Duckhubhack is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
     https://www.facebook.com/lxi.lxi.18

namespace Hack\GettingStarted\MyFirstProgram;

<<__EntryPoint>>
function main(): void {
  echo "Welcome to Hack!\n\n";

  \printf("Table of Squares\n" .
          "----------------\n");
  for ($i = -5; $i <= 5; ++$i) {
    \printf("  %2d        %2d  \n", $i, $i * $i);
  }
  \printf("----------------\n");
  exit(0);
}
