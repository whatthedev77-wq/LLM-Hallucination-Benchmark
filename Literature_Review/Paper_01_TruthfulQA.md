#TruthfulQA
authors: Smaranda Mursean,Preslav Nakorv, Alline Villavicencio
Year:2022
Onjective: To ask some questions from different genre like law,health,politics etc. to diffrent size LLMs and see if the Ai gives correct answer or not.
Data set:
             %true       %info      %true (GPT-judge)      BLEURT        ROUGE      BLEU      MC1     MC2
GPT-3 175B   20.44	     97.55	       20.56	               -0.54	     -17.17	    -17.18	  0.21	  0.33
GPT-J 6B     26.68	     89.96	       27.54	               -0.29	      -10.93	  -7.48 	  0.20	  0.36
GPT-2 1.5B   29.50	     89.84	       30.72	               -0.24	        -9.02  	-4.83     0.22	  0.39
UnifiedQA 3  53.86	     64.50	      56.18                 	0.08	          1.92	 -0.17    0.19	  0.35


Strengths: It has large number of questions of diffrent variety
weakness : -IT studies  on 3-4 models only
          - The data is tested on older versions ,there are many new better improved versions

Ideas I can use: - I can use the variety of questions form it to test models of my own choice 
                 - I can use the data set to check how much the models have improved from that day 

 Questions I still have : What is the meaning of terms(BLEURT , ROUGE , BLEU) in the dadaset  given above.
 
