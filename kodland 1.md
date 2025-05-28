meme_dict = {
    "CRINGE": "Sesuatu yang sangat aneh atau memalukan",
    "LOL": "Tanggapan umum terhadap sesuatu yang lucu",
    "ROFL": "Tanggapan terhadap lelucon",
    "SHEESH": "Sedikit ketidaksetujuan",
    "CREEPY": "Menakutkan, tidak menyenangkan",
    "AGGRO": "Untuk menjadi agresif/marah",
    "NIGGERS": "orang berkulit hitam (kadang kadang sinting)"
}

word = input("Ketik kata yang tidak Kamu mengerti (boleh huruf besar atau kecil): ")
word_upper = word.upper()

if word_upper in meme_dict:
    print(meme_dict[word_upper])
else:
    print("Maaf, kata itu tidak ada dalam kamus el Cringe kami lawak cik.")
