- 👋 Hi, I’m @Dezarzi
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Dezarzi/Dezarzi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# install.packages("colorfindr") 
# install.packages("tidyverse") 
# install.packages("palmerpenguins")
library(colorfindr) 
library(tidyverse)
get_colors("images/"wp6751189.png") %>% 
  make_palette(n = 5)
