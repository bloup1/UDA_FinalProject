# UDA_FinalProject
Final project for UDA 
CID: 02257544 (this report is the result of my independent work)
Guillaume Dechambre

**Files detail**:
-  input BOE 'minutes':     boe_all_minutes.txt
-  BOE meeting date:        boe_meeting_dates.txt
-  uncertainty lexico:      uncertainty_words_finlex_plus_lm.txt
-  lda model trained:       lda_model_used + lda_model_used.expElogbeta.npy + lda_model_used.id2word + lda_model_used.state
-  LDAVIS MDS view of LDA:  ldavis_mds_6_topics.html

**Jupyter Notebook**:       UDA_FinalProject_Dechambre.ipynb

**Instructions for Jupyter Notebook**
Please run sequentially:
-  run section **Libraries**
-  run section **Global Variables**
-  run section **Pre-Processing** for parsing the raw data: run with {_load_saved_boe_data_} = False the first time. It will add 10 minutes to parse the 164 'minutes'.
-  run section **Building Model** for training the model: run with {_run_lda_model_} = False if one wants to pick up serialized saved model (uploaded). Setting to true takes ~20minutes.
-  run section **Topic Proportions Through Time** for that visualization.
-  run section **Clustering, Topic Proportions Correlation and Word Cloud** for those visualizations.
-  run section **Parameters Tuning** for finding max coherence parameters (individually): there are 5 parameters: number of passes, number of topics, eta, alpha and the LDA seed. Each takes about 20 minutes to run.


Happy New Year!
