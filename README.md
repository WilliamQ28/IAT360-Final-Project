IAT 360 Final Project Submission
gen_text.py calls hugging face API so make sure to add your hugging face access token in blyat.txt

run with 
pip install requests
python gen_text.py --sections 4 --content_type "tech company" --tone "confident and clear" --audience "a general audience evaluating the offering" --token_file hf_token.txt --out output_staged.json
