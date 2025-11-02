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


