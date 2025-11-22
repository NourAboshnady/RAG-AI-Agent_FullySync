# RAG-AI-Agent_FullySync

**What it actually does** ?

I have one folder on Google Drive called "Apple Reports".

Every time I drop any new Apple file in it (10-K, 10-Q, earnings transcript, press release, whatever PDF),  
the system wakes up by itself, reads the file, chunks it, creates embeddings, and pushes everything to Pinecone.

30 seconds later I can ask anything about that new file (or any old file) and it answers instantly with exact page number.

That’s literally it.

**No manual steps. No rerun. No “python ingest.py”. Just drop → ask → done.**

Example:  
I just dropped Apple’s 2024 10-K → asked “What was iPhone revenue this year?” → got the exact number + Page 34 in 2 seconds.

Works 24/7 even when my laptop is off.

That’s the whole project. Nothing more, nothing less.

Try it and star if you like it 🚀
