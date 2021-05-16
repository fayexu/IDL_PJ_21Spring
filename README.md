# IDL_PJ_21Spring

This is a two-stages method to generate adversarial examples for reducing gender bias in pre-trained models.

First stage, filtering candidate sentences from an open NLI dataset. Just run Filter.ipynb. After this step, it will output a file named train_full_filtered.txt.

In the second stage, to generate the adversarial examples to finetune the pre-trianed model, run the "generate_both.ipynb", it will output a file named out.txt.

Then, you can run "run_mlm_adv.ipynb" to finetune the selected models.

In addition, we investigate the gender bias of models on our genertated dataset before and after finetuning respectively, run the file "DistilBert.ipynb".

More details of this project are shown in report in file named"IDL_21_project_final.pdf"

