<<<<<<< HEAD
Bootstrap:docker
From:sachet/polysolver:v4
=======
BootStrap:docker
From: sachet/polysolver:v4
>>>>>>> 4430a9fc0ea87249ca10409a3f11c28f8fb44193

%post

     mkdir /data/
     mv /home/polysolver /usr/local/libexec/polysolver
     mv /home/samtools /usr/local/libexec/samtools
     export PSHOME=/usr/local/libexec/polysolver
     export SAMTOOLS_DIR=/usr/local/libexec/samtools
     export JAVA_DIR=/usr/bin
     export NOVOALIGN_DIR=$PSHOME/binaries

     # IMPORTANT: the below aren't set, I'm not sure where they are inside image
     export GATK_DIR=$PSHOME
     export MUTECT_DIR=$PSHOME
     export STRELKA_DIR=$PSHOME
     chmod 777 -R /usr/local/libexec
<<<<<<< HEAD

=======
>>>>>>> 4430a9fc0ea87249ca10409a3f11c28f8fb44193
