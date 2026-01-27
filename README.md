*Note: In `generate_tickets.py`, there is a glitch the produces an errored pdf when you run functions `create_ticket_pdfs()` & `consolidate_pdfs()` in sequence. Below are steps to work around this issue:

1. Fill qr folder with all the qr's to be used. (Qr images must be named by their ticket #)
2. Open `generate_tickets.py` 
3. comment out `consolidate_pdfs()`
4. Run the script (press play in PyCharm)
5. Now uncomment `consolidate_pdfs()` and comment out `create_ticket_pdfs()`
6. Run script again 
7. This should create a `cet_printable_tickets.pdf`