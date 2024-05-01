# Simple Retrieval-Augmented Generation (RAG)

This project shows how a basic RAG model with a history can be used.


## Install

Clone the repo and install the requirements.txt:

```bash 
  pip install -r requirements.txt
```   
## Examples

```bash 
Question:
My car dripping something dark on the floor, what that it means?

Answer:
If your car is dripping something dark on the floor, it could indicate an oil leak.
It is important to have your vehicle checked by a professional to determine 
the source of the leak and to prevent any further damage.

All relevant pages:
422, 410, 414, 531
```   

```bash 
Question:
Where could be the source?

Answer:
The source of the oil leak could be various components in the vehicle's engine or
transmission system. It is recommended to have your vehicle checked by a professional 
to accurately determine the source of the leak.

All relevant pages:
299, 9, 424, 153
```