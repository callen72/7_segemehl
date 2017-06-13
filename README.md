# 7_segemehl
http://www.bioinf.uni-leipzig.de/Software/segemehl/ 

./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTair3_S3_R1_001.fastq > mymap_WTair3.sam 
./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTeth1_S4_R1_001.fastq > mymap_WTeth1.sam
./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTeth2_S7_R1_001.fastq > mymap_WTeth2.sam
./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTeth3_S8_R1_001.fastq > mymap_WTeth3.sam
(Run for each .fastq file)
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTair2_S2_R1_001.fastq > mymap2.sam
[SEGEMEHL] Mon Jun 12 13:00:56 2017: reading queries in 'WTair2_S2_R1_001.fastq'.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: 23114903 query sequences found.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading database sequences.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: 5 database sequences found.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: total length of db sequences: 3947019
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading suffix array '6803genome.idx' from disk.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading lcpc/vtab.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading childtab.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading suflinks.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading lsint id.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: read suffix array '6803genome.idx' with 3947024 elements.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: md5 keys of index and db match.
[SEGEMEHL] Mon Jun 12 13:03:10 2017: reading the suffix array has taken 0.000000 seconds.
[SEGEMEHL] Mon Jun 12 14:13:19 2017: matching w/ suffixarray has taken 4209.000000 seconds.
[SEGEMEHL] Mon Jun 12 14:13:19 2017:
Goodbye.
 "Wir sind hier nicht in Seattle Dirk!" (Tocotronic)


/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>ls
6803genome.fa   Makefile.SUNOS          WTair2_S2_R1_001.fastq
6803genome.idx  mymap.sam               WTair3_S3_R1_001.fastq
gene.gff        segemehl_0_2_0.tar      WTeth1_S4_R1_001.fastq
lack.x          segemehl.x              WTeth2_S7_R1_001.fastq
libs            src                     WTeth3_S8_R1_001.fastq
Makefile        testrealign.x
Makefile~       WTair1_S1_R1_001.fastq
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>nano mymap_WTair1.sam
@HD     VN:1.0
@SQ     SN:NC_000911.1  LN:3573470
@SQ     SN:NC_005230.1  LN:103307
@SQ     SN:NC_005231.1  LN:44343
@SQ     SN:NC_005229.1  LN:119895
@SQ     SN:NC_005232.1  LN:106004
@PG     ID:segemehl     VN:0.2.0-$Rev: 418 $ ($Date: 2015-01-05 05:17:35 -0500 (Mon, 05 Jan 2015) $)    CL:./segemehl.x -i$
NB501060:48:H72KVBGXY:1:11101:5234:1049 1:N:0:GTCCGC    16      NC_000911.1     2376211 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:18055:1050 1:N:0:GTCCGC   0       NC_000911.1     3316917 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:5322:1050 1:N:0:GTCCGC    0       NC_000911.1     3316763 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:22324:1051 1:N:0:GTCCGC   0       NC_000911.1     3316793 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:22293:1052 1:N:0:GTCCGC   0       NC_000911.1     3316946 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:11843:1053 1:N:0:GTCCGC   0       NC_005232.1     82535   255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:24049:1054 1:N:0:GTCCGC   0       NC_000911.1     3316764 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:3314:1056 1:N:0:GTCCGC    16      NC_000911.1     673073  255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:8781:1060 1:N:0:GTCCGC    16      NC_000911.1     153429  255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:15349:1062 1:N:0:GTCCGC   0       NC_000911.1     1819845 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:15349:1062 1:N:0:GTCCGC   16      NC_000911.1     7307    255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:20493:1062 1:N:0:GTCCGC   16      NC_000911.1     1679174 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:21087:1064 1:N:0:GTCCGC   16      NC_000911.1     1679078 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:14629:1064 1:N:0:GTCCGC   0       NC_000911.1     3316976 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:15638:1065 1:N:0:GTCCGC   0       NC_000911.1     3316888 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:2178:1066 1:N:0:GTCCGC    16      NC_000911.1     1679156 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:11088:1067 1:N:0:GTCCGC   16      NC_000911.1     1679175 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:5734:1068 1:N:0:GTCCGC    0       NC_000911.1     3316795 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:19613:1069 1:N:0:GTCCGC   16      NC_000911.1     958030  255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:22005:1071 1:N:0:GTCCGC   16      NC_000911.1     1679147 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:3273:1072 1:N:0:GTCCGC    0       NC_000911.1     3316985 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:10961:1075 1:N:0:GTCCGC   16      NC_000911.1     1679142 255     75M     *       0       0 $
NB501060:48:H72KVBGXY:1:11101:5811:1076 1:N:0:GTCCGC    0       NC_000911.1     3316919 255     1M1I73M *       0       0 $

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>ls -l
total 60941220
-rwxr-xr-x 1 callen72 users    3996723 Apr 18 12:26 6803genome.fa
-rw-r--r-- 1 callen72 users   55991061 Jun 12 11:23 6803genome.idx
-rwxr-xr-x 1 callen72 users    1385252 Apr 18 12:27 gene.gff
-rwxr-xr-x 1 callen72 users    1487989 Jun 12 11:20 lack.x
drwxr-xr-x 3 callen72 users      12288 Jun 12 11:20 libs
-rw-r--r-- 1 callen72 users       5070 Jan  7  2015 Makefile
-rw-r--r-- 1 callen72 users       5070 Jan  5  2015 Makefile~
-rw-r--r-- 1 callen72 users       1067 Jan  5  2015 Makefile.SUNOS
-rw-r--r-- 1 callen72 users 5821820628 Jun 12 13:49 mymap_WTair1.sam
-rw-r--r-- 1 callen72 users 6500116833 Jun 12 14:13 mymap_WTair2.sam
-rw-r--r-- 1 callen72 users 5663426912 Jun 12 14:57 mymap_WTair3.sam
-rw-r--r-- 1 callen72 users 6259288158 Jun 12 15:56 mymap_WTeth1.sam
-rw-r--r-- 1 callen72 users 5642861549 Jun 12 16:49 mymap_WTeth2.sam
-rw-r--r-- 1 callen72 users 5882260096 Jun 12 18:07 mymap_WTeth3.sam
-rw-r--r-- 1 callen72 users       2972 Apr 19  2012 processMerged.pl
-rw-r--r-- 1 callen72 users    4536320 Apr 18 12:24 segemehl_0_2_0.tar
-rwxr-xr-x 1 callen72 users    1512082 Jun 12 11:20 segemehl.x
drwxr-xr-x 2 callen72 users       4096 Apr 18 12:22 src
-rwxr-xr-x 1 callen72 users    1414126 Apr 18 12:22 testrealign.x
-rw-r--r-- 1 callen72 users 4427981083 Apr 18 12:25 WTair1_S1_R1_001.fastq
-rw-r--r-- 1 callen72 users 4835516675 Apr 18 12:25 WTair2_S2_R1_001.fastq
-rw-r--r-- 1 callen72 users 4188371450 Apr 18 12:25 WTair3_S3_R1_001.fastq
-rw-r--r-- 1 callen72 users 4637692584 Apr 18 12:25 WTeth1_S4_R1_001.fastq
-rw-r--r-- 1 callen72 users 4147069520 Apr 18 12:25 WTeth2_S7_R1_001.fastq
-rw-r--r-- 1 callen72 users 4326615469 Apr 18 12:25 WTeth3_S8_R1_001.fastq


./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTeth3_S8_R1_001.fastq --threads 8 > mymap_WTeth3.sam (Run for each sam and fastq file)

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>./segemehl.x -i 6803genome.idx -d 6803genome.fa -q WTair1_S1_R1_001.fastq --threads 8 > mymap_WTair1.sam
[SEGEMEHL] Mon Jun 12 19:12:59 2017: reading queries in 'WTair1_S1_R1_001.fastq'.
[SEGEMEHL] Mon Jun 12 19:15:18 2017: 21166775 query sequences found.
[SEGEMEHL] Mon Jun 12 19:15:18 2017: reading database sequences.
[SEGEMEHL] Mon Jun 12 19:15:18 2017: 5 database sequences found.
[SEGEMEHL] Mon Jun 12 19:15:18 2017: total length of db sequences: 3947019
[SEGEMEHL] Mon Jun 12 19:15:18 2017: reading suffix array '6803genome.idx' from disk.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: reading lcpc/vtab.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: reading childtab.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: reading suflinks.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: reading lsint id.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: read suffix array '6803genome.idx' with 3947024 elements.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: md5 keys of index and db match.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: reading the suffix array has taken 1.000000 seconds.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: starting 8 threads.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2646072 reads in thread 0.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645855 reads in thread 1.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645808 reads in thread 2.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645808 reads in thread 3.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645808 reads in thread 4.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645808 reads in thread 5.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645808 reads in thread 6.
[SEGEMEHL] Mon Jun 12 19:15:19 2017: 2645808 reads in thread 7.
[=========================]   99%(21166173)  reads matched.  /
[SEGEMEHL] Mon Jun 12 19:24:27 2017: threaded matching w/ suffixarray has taken 548.000000 seconds.
[SEGEMEHL] Mon Jun 12 19:24:27 2017:
Goodbye.
 "Die Ficker!" (Thommy)

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>nano mymap_WTair1.sam
@HD     VN:1.0
@SQ     SN:NC_000911.1  LN:3573470
@SQ     SN:NC_005230.1  LN:103307
@SQ     SN:NC_005231.1  LN:44343
@SQ     SN:NC_005229.1  LN:119895
@SQ     SN:NC_005232.1  LN:106004
@PG     ID:segemehl     VN:0.2.0-$Rev: 418 $ ($Date: 2015-01-05 05:17:35 -0500 (Mon, 05 Jan 2015) $)    CL:$
NB501060:48:H72KVBGXY:4:13611:25241:6878 1:N:0:GTCCGC   16      NC_000911.1     1679037 255     75M     *  $
NB501060:48:H72KVBGXY:1:13311:21039:8154 1:N:0:GTCCGC   16      NC_000911.1     1679142 255     75M     *  $
NB501060:48:H72KVBGXY:3:21402:23243:4054 1:N:0:GTCCGC   0       NC_000911.1     1818911 255     75M     *  $
NB501060:48:H72KVBGXY:3:21402:23243:4054 1:N:0:GTCCGC   16      NC_000911.1     8241    255     75M     *  $
NB501060:48:H72KVBGXY:3:11407:16510:1470 1:N:0:GTCCGC   16      NC_000911.1     1679174 255     75M     *  $
NB501060:48:H72KVBGXY:2:21102:6111:9664 1:N:0:GTCCGC    0       NC_000911.1     854496  255     75M     *  $

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/analysis/7_segemehl/segemehl>ls -l
total 60941188
-rwxr-xr-x 1 callen72 users    3996723 Apr 18 12:26 6803genome.fa
-rw-r--r-- 1 callen72 users   55991061 Jun 12 11:23 6803genome.idx
-rwxr-xr-x 1 callen72 users    1385252 Apr 18 12:27 gene.gff
-rwxr-xr-x 1 callen72 users    1487989 Jun 12 11:20 lack.x
drwxr-xr-x 3 callen72 users      12288 Jun 12 11:20 libs
-rw-r--r-- 1 callen72 users       5070 Jan  7  2015 Makefile
-rw-r--r-- 1 callen72 users       5070 Jan  5  2015 Makefile~
-rw-r--r-- 1 callen72 users       1067 Jan  5  2015 Makefile.SUNOS
-rw-r--r-- 1 callen72 users 5821820640 Jun 12 19:24 mymap_WTair1.sam
-rw-r--r-- 1 callen72 users 6500116845 Jun 12 19:39 mymap_WTair2.sam
-rw-r--r-- 1 callen72 users 5663426924 Jun 12 19:52 mymap_WTair3.sam
-rw-r--r-- 1 callen72 users 6259288170 Jun 12 20:31 mymap_WTeth1.sam
-rw-r--r-- 1 callen72 users 5642861561 Jun 12 20:06 mymap_WTeth2.sam
-rw-r--r-- 1 callen72 users 5882260108 Jun 12 20:20 mymap_WTeth3.sam
-rw-r--r-- 1 callen72 users       2972 Apr 19  2012 processMerged.pl
-rw-r--r-- 1 callen72 users    4536320 Apr 18 12:24 segemehl_0_2_0.tar
-rwxr-xr-x 1 callen72 users    1512082 Jun 12 11:20 segemehl.x
drwxr-xr-x 2 callen72 users       4096 Apr 18 12:22 src
-rwxr-xr-x 1 callen72 users    1414126 Apr 18 12:22 testrealign.x
-rw-r--r-- 1 callen72 users 4427981083 Apr 18 12:25 WTair1_S1_R1_001.fastq
-rw-r--r-- 1 callen72 users 4835516675 Apr 18 12:25 WTair2_S2_R1_001.fastq
-rw-r--r-- 1 callen72 users 4188371450 Apr 18 12:25 WTair3_S3_R1_001.fastq
-rw-r--r-- 1 callen72 users 4637692584 Apr 18 12:25 WTeth1_S4_R1_001.fastq
-rw-r--r-- 1 callen72 users 4147069520 Apr 18 12:25 WTeth2_S7_R1_001.fastq
-rw-r--r-- 1 callen72 users 4326615469 Apr 18 12:25 WTeth3_S8_R1_001.fastq

./segemehl.x -x 6803genome.ctidx -y 6803genome.gaidx -d 6803genome.fa -F [1 or 2]
htseq-count -s no -t gene -i ID mymap_WTair1.sam gene.gff > mymap_WTair1_counts.txt
