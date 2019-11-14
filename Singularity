Bootstrap:docker
From:sachet/polysolver:v4

%post

     mkdir /data/
     mv /home/polysolver /usr/local/libexec/polysolver
     mv /home/samtools /usr/local/libexec/samtools
     export PSHOME=/usr/local/libexec/polysolver
     export SAMTOOLS_DIR=/usr/local/libexec/samtools
     export JAVA_DIR=/usr/bin
     export NOVOALIGN_DIR=$PSHOME/binaries
