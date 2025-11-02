PROJECT NO. 01 & 02


WhatsApp and Telegram RAG AI Agent

I built a RAG (Retrieval-Augmented Generation) AI assistant that answers questions regarding their subject, topic and chapter in WhatsApp.

What This Project Does
RAG System: Uses Retrieval-Augmented Generation to provide accurate answers from the PDF curriculum books stored in supabase vector store .

Used the PDF books of curriculum as the primary data source for retrieval and context generation.

Chat with Document: Ask questions on WhatsApp or telegram, and the AI finds specific answers from the subject book.

Built with n8n: Created the entire RAG agent visually using n8n work flow tool.

WhatsApp Integration: Used WhatsApp as the trigger for conversations.

Telegram Integration: Used Telegram as the trigger for conversations.

Supabase vector store : Stored and searched document embedding in supabase.

Google Gemini: Used Gemini model for embedding and generating responses.

How It Works
You send a question on WhatsApp or telegram (trigger).

My n8n RAG workflow searches Supabase for relevant information from the subject wise pdf file.

Google Gemini processes the context and sends accurate answers back to WhatsApp or telegram.



PROJECT NO. 03


Multilingual speech to text

I built a multilingual transcribing automation system.

What This Project Does

Multilingual transcribing System: Uses speeches delivered in schools, colleges and university then transcribe it to text and also can translate to any language then stored in supabase vector store .

Used the speeches as the primary data source for transcribing and translation.


Built with n8n: Created the entire Transcribing automation visually using n8n work flow tool.

Audio file uploader: Used audio file uploader as a trigger.

Google gemini transcriber : used google gemini transcribe to covert speech to text.

Google doc: Used google doc to save transcribed text.

Google translator: used google translator to translate text to any language

How It Works

upload audio file to file uploader

google gemini transcribe the audio into text

google translator translate the text from one language to other

google docs save the text after transcribe or translate.

Supabase vector store: vectorize the text through google gemini embedding module and store the data






