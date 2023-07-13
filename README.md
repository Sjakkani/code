  204  cd project/
  205  ls -l
  206  ls -la
  207  git status
  208  git branch
  209  git checkout dev
  210  git ls-files
  211  ll
  212  touch dev.txt
  213  git status
  214  git add .
  215  git status
  216  git status
  217  git branch
  218  git checkout master
  219  git status
  220  git checkout dev
  221  git commit . -m "Dev: dev.txt"
  222  git status
  223  git ls-files
  224  ll
  225  git checkout master
  226  ll
  227  git ls-files
  228  git branch
  229  git branch
  230  git branch qa
  231  git ls-files
  232  git branch
  233  git checkout qa
  234  ll
  235  git branch
  236  git merge dev
  237  ll
  238  git branch
  239  ll
  240  vi program.txt 
  241  git status
  242  git commit . -m "Comm: from QA"
  243  git status
  244  git checkout dev
  245  vi program.txt 
  246  git commit -a -m "adding a line in dev branch"
  247  git checkout qa
  248  git branch
  249  git merge dev
  250  git config merge.tool vimdiff
  251  git config merge.conflictstyle diff3
  252  git config mergetool.prompt false
  253  git mergetool
  254  ls -l
  255  cat program.txt
  256  cat program.txt.orig 
  257  rm program.txt.orig 
  258  ll
  259  git status
  260  git commit -a -m "Merged data from Dev"
  261  git status
  262  git branch
  263  cat program.txt 
  264  history
  265  ll
  266  vi dev.txt 
  267  vi dev.txt 
  268  cat dev
  269  cat dev.txt 
  270  git branch
  271  git branch
  272  git checkout master
  273  git status
  274  git commit -a -m "new data"
  275  git checkout dev
  276  git branch
  277  git checkout master
  278  git branch
  279  git branch -M main
  280  git branch
  281  git remote -v
  282  git remote
  283  git remote add origin https://github.com/raghuopsdev/tmpkelly.git
  284  git remote -v
  285  git push -u origin main
  286  git push -u origin main
  287  git branch
  288  git push -u origin dev
  289  git push -u origin dev
  290  history
 125  which git
  126  whereis git
  127  git --version
  128  yum repolist
  129  yum repolist all
  130  yum list | grep git
  131  yum install git
  132  whoami
  133  sudo yum install git
  134  git --version
  135  whereis git
  136  which git
  137  pwd
  138  mkdir project
  139  pwd
  140  cd project
  141  ls -l
  142  ls -la
  143  touch program.txt
  144  ls -l
  145  git init
  146  ls -l
  147  ls -la
  148  ls -l
  149  ll
  150  git status
  151  git add program.txt 
  152  git status
  153  ls -l
  154  git commit . -m "V1"
  155  git config --global --edit
  156  git commit --amend --reset-author
  157  git status
  158  ls -l
  159  git ls-files
  160  history
  161  vi program.txt 
  162  git status
  163  git add .
  164  git status
  165  git restore --staged program.txt
  166  git status
  167  git add .
  168  git commit . -m "V2"
  169  git status
  170  git ls-files
  171  git log
  172  ll
  173  vi program.txt 
  174  git commit -a -m "V2"
  175  git log
  176  ll
  177  rm program.txt 
  178  ll
  179  ls -l
  180  git ls-files
  181  git log
  182  git commit --amend --reset-author
  183  git log
  184  git checkout program.txt
  185  ll
  186  cat program.txt 
  187  git status
  188  rm program.txt
  189  git status
  190  git log
  191  git checkout 67dc62bbc8c467337d06557cd12314bb55b11174
  192  git log
  193  ll
  194  cat program.txt 
  195  vi program.txt 
  196  git status
  197  git checkout
  198  git log
  199  git checkout master
  200  git log
  201  ll
  202  cat program.txt 
  203  git status
  204  history
  205  git branch
  206  git branch dev
  207  git branch
  208  git checkout dev
  209  git branch
  210  git ls-files
  211  ls -l
  212  vi program.txt
  213  git status
  214  git commit -a -m "Dev:V4"
  215  git status
  216  git log
  217  git branch
  218  git checkout master
  219  git log
  220  cat program.txt 
  221  git ls-files
  222  history
207  git status
  208  git branch
  209  git checkout dev
  210  git ls-files
  211  ll
  212  touch dev.txt
  213  git status
  214  git add .
  215  git status
  216  git status
  217  git branch
  218  git checkout master
  219  git status
  220  git checkout dev
  221  git commit . -m "Dev: dev.txt"
  222  git status
  223  git ls-files
  224  ll
  225  git checkout master
  226  ll
  227  git ls-files
  228  git branch
  229  git branch
  230  git branch qa
  231  git ls-files
  232  git branch
  233  git checkout qa
  234  ll
  235  git branch
  236  git merge dev
  237  ll
  238  git branch
  239  ll
  240  vi program.txt 
  241  git status
  242  git commit . -m "Comm: from QA"
  243  git status
  244  git checkout dev
  245  vi program.txt 
  246  git commit -a -m "adding a line in dev branch"
  247  git checkout qa
  248  git branch
  249  git merge dev
  250  git config merge.tool vimdiff
  251  git config merge.conflictstyle diff3
  252  git config mergetool.prompt false
  253  git mergetool
  254  ls -l
  255  cat program.txt
  256  cat program.txt.orig 
  257  rm program.txt.orig 
  258  ll
  259  git status
  260  git commit -a -m "Merged data from Dev"
  261  git status
  262  git branch
  263  cat program.txt 
  264  history
  265  ll
  266  vi dev.txt 
  267  vi dev.txt 
  268  cat dev
  269  cat dev.txt 
  270  git branch
  271  git branch
  272  git checkout master
  273  git status
  274  git commit -a -m "new data"
  275  git checkout dev
  276  git branch
  277  git checkout master
  278  git branch
  279  git branch -M main
  280  git branch
  281  git remote -v
  282  git remote
  283  git remote add origin https://github.com/raghuopsdev/tmpkelly.git
  284  git remote -v
  285  git push -u origin main
  286  git push -u origin main
  287  git branch
  288  git push -u origin dev
  289  git push -u origin dev
  290  history
  291  cd project/
  292  ll
  293  ls -la
  294  git remote -v
  295  git ls-files
  296  ll
  297  git pull origin main
  298  ll
  299  ls -l
  300  git ls-files
  301  ll
  302  git remote -v
  303  git fetch origin main
  304  git ls-files
  305  git fetch origin main
  306  ll
  307  git pull origin main
  308  ll
  309  git branch
  310  git branch
  311  vi rebase.txt
  312  git add .
  313  git commit . -m "rebase exercise"
  314  git ls-files
  315  git branch feature
  316  git branch
  317  git checkout feature
  318  git branch
  319  git ls-files
  320  vi rebase.txt 
  321  git commit -a -m "second line"
  322  git status
  323  cat rebase.txt 
  324  git checkout main
  325  cat rebase.txt 
  326  git rebase feature
  327  git branch
  328  cat rebase.txt 
  329  git log
  330  git branch
  331  git revert
  332  git log
  333  git revert 6df54d5ebba0468e90156039547fd14c142f0b4d
  334  ll
  335  cat rebase.txt 
  336  git revert --continue
  337  cat rebase.txt 
  338  git status
  339  git commit -a -m "revert demo"
  340  cat rebase.txt 
  341  git revert --skip
  342  git log
  343  git branch
  344  ll
  345  git checkout qa
  346  ll
  347  git branch main
  348  git checkout main
  349  ll
  350  git log
  351  git branch
  352  git checkout qa
  353  git cherry-pick 11e4a5bf7d8e07f4f8eaed8af7a1fbfdaba31dd9
  354  ll
  355  cat fetch.txt 
  356  git branch
  357  ls -la
  358  git branch
  359  git ls-files
  360  vi temp.txt
  361  git add .
  362  git status
  363  git checkout main
  364  git status
  365  git branch
  366  vi main.txt
  367  git stash
  368  git status
  369  git add .
  370  git commit -m "main.txt"
  371  git stash list
  372  git stash --help
  373  git stash apply
  374  git checkout qa
  375  git status
  376  git commit . -m "qa"
  377  history378  yum repolist all
  379  yum list | grep httpd
  380  mkdir soft
  381  cd soft
  382  wget https://dlcdn.apache.org/httpd/httpd-2.4.57.tar.gz
  383  ll
  384  ls -lrth
  385  tar -xzvf httpd-2.4.57.tar.gz 
  386  ll
  387  cd httpd-2.4.57/
  388  ls
  389  ./configure 
  390  yum list | grep apr
  391  yum install apr
  392  yum install apr-devel
  393  ./configure 
  394  yum list | grep apr
  395  yum install apr-util-devel
  396  ./configure 
  397  cat config.log 
  398  yum install gcc
  399  ./configure 
  400  yum install pcre
  401  ./configure
  402  yum list | grep pcre
  403  yum install pcre-devel
  404  ./configure
  405  ls
  406  which make
  407  make
  408  make install
  409  cd /usr/local/apache2/
  410  ll
  411  cd bin/
  412  ll
  413  ./apachectl -k start
  414  ps -ef | grep httpd
  415  cd ..
  416  pwd
  417  ll
  418  ll
  419  cd ..
  420  cd /home/ec2-user/
  421  ll
  422  cd soft/
  423  ll
  424  git clone https://github.com/raghuopsdev/hello-world-1.git
  425  ll
  426  cd hello-world-1/
  427  ll
  428  yum list | grep tomcat
  429  which tomcat9
  430  history | grep tomcat
  431  cd /etc/tomcat9/
  432  tomcat9 start
  433  cd /home/ec2-user/apache-tomcat-8.5.90/
  434  ll
  435  cd bin/
  436  ll
  437  ./startup.sh 
  438  ps -ef | grep tomcat
  439  cd /home/ec2-user/
  440  ll
  441  cd soft/hello-world-1/
  442  ll
  443  which maven
  444  yum list | grep maven
  445  yum install maven
  446  which maven
  447  which mvn
  448  whereis mvn
  449  mvn --version
  450  pwd
  451  ll
  452  yum install tree
  453  ll
  454  tree server
  455  tree webapp/
  456  ll
  457  ll
  458  vi pom.xml 
  459  mvn --version
  460  java --version
  461  mvn clean install
  462  java --version
  463  yum list | grep open
  464  yum list | grep openjdk
  465  yum list | grep java
  466  yum list | grep openjdk
  467  yum list | grep openjava
  468  yum list | grep open
  469  yum list | grep java
  470  yum repolist all
  471  yum install -y java-1.8.0-amazon-corretto-devel.x86_64
  472  java -version
  473  which java
  474  cd /usr/lib
  475  ll
  476  cd java
  477  ll
  478  which java
  479  ll /usr/bin/java
  480  ll /etc/alternatives/java
  481  alternatives --config java
  482  alternatives --config java
  483  java -version
  484  cd /home/ec2-user/soft/hello-world-1/
  485  ll
  486  mvn clean install
  487  cd ..
  488  wget https://builds.openlogic.com/downloadJDK/openlogic-openjdk/17.0.5+8/openlogic-openjdk-17.0.5+8-linux-x64.tar.gz
  489  ll
  490  tar -xzvf openlogic-openjdk-17.0.5+8-linux-x64.tar.gz 
  491  ll
  492  cd openlogic-openjdk-17.0.5+8-linux-x64/
  493  ll
  494  cd bin/
  495  ll
  496  ./java --version
  497  java --version
  498  which java
  499  ll /usr/bin/java
  500  ll /etc/alternatives/java
  501  cd /etc/alternatives/
  502  ll
  503  ll java
  504  ln -s java9 /home/ec2-user/soft/openlogic-openjdk-17.0.5+8-linux-x64/bin/java
  505  ln -s /home/ec2-user/soft/openlogic-openjdk-17.0.5+8-linux-x64/bin/java java17
  506  ll java17
  507  rm java
  508  mv java17 java
  509  java --version
  510  cd /home/ec2-user/soft/hello-world-1/
  511  mvn --version
  512  vi /etc/maven/settings.xml 
  513  echo $JAVA_HOME
  514  export JAVA_HOME=/home/ec2-user/soft/openlogic-openjdk-17.0.5+8-linux-x64/bin/
  515  mvn --version
  516  export JAVA_HOME=/home/ec2-user/soft/openlogic-openjdk-17.0.5+8-linux-x64/
  517  mvn --version
  518  mvn clean install
  519  mvn --version
