This is a Retrieval-Augmented Generation (RAG) backend built in Python + FastAPI + SQLite, created for the Translated – Junior ML Engineer Test.

It exposes three endpoints:

Endpoint	Method	Purpose
/pairs	POST	: Add new translation pair
/prompt	GET	: Retrieve up to 4 similar examples (RAG)
/stammering	GET	: Detect repetition (“stammering”) in a translation
