# repository-of-names
Hafsjór af heitum
Einfalt forrit sem kemur með tillögu að nafni fyrir Github-svæði (repository) úr skrá yfir örnefni úr hafi frá [thdg](https://github.com/thdg/ornefni)

`sjor <- readr::read_table("https://raw.githubusercontent.com/thdg/ornefni/master/data/usjavarornefni.txt");
N <- seq(1,nrow(sjor));
tolower(iconv(sjor[sample(N,1),], "UTF-8", "WINDOWS-31J"))`
