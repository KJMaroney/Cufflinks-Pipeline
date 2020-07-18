# Cufflinks-Pipeline
Cufflinks counting -> EdgeR. Basically a defunct pipeline that nobody will ever use unless systemPipeR doesn't work. Enjoy

Numerous people have stated that it is not good practice to use Cufflinks for counting and then reroute through EdgeR because Cufflinks has its own way to determine differential expression. However, EdgeR is more the industry standard at this point and the only point of using cufflinks for counting is, again, if there is obvious buildup that is not being counted because these reads align in multiple locations and conservative modern counting software are throwing these away.
