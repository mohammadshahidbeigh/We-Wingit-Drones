Check python version:
python3 --version

Check pip version:
pip -- version

Install pip:
python3 -m ensurepip --upgrade

Install the OpenAI CLI:
pip install --upgrade openai
Install pandad:
$ pip install openai pandas

Add our API key:
export OPENAI_API_KEY="<OPENAI_API_KEY>"
for example":
export OPENAI_API_KEY="sdk-3344fnjsfknfwGDFR-34dhG"

    To navigate to the folder holding the data, we use the cd (change directory) command:
        cd Documents/apps/we-wingit


Start the data preparation and use the -f flag to identify the file where our data is stored:
openai tools fine_tunes.prepare_data -f <LOCAL_FILE>
for example:
openai tools fine_tunes.prepare_data -f we-wingit-data.csv

To create a fine-tuned model
openai api fine_tunes.create -t <TRAIN_FILE_ID_OR_PATH> -m <BASE_MODEL>
for example:
openai api fine_tunes.create -t we-wingit-data_prepared.jsonl -m davinci

To reconnect the stream (to check how the fine-tune is progressing or see if it has completed)
openai api fine_tunes.follow -i <YOUR_FINE_TUNE_JOB_ID>
for example:
openai api fine_tunes.follow -i ft-bfubdoni4737dbsj
