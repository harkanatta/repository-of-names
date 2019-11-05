# repository-of-names
## Hafsjór af heitum
Nokkrar línur í R sem birta tillögu að slóð fyrir ný Github-svæði (repository) hjá mér. Tekið úr textaskrá yfir örnefni úr hafi frá [thdg](https://github.com/thdg/ornefni)

`sjor <- read.table("https://raw.githubusercontent.com/thdg/ornefni/master/data/usjavarornefni.txt",encoding = "UTF-8");
N <- seq(1,nrow(sjor));
tolower(iconv(sjor[sample(N,1),], "UTF-8", "WINDOWS-31J"))`
