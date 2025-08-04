# vi data_processing.py
train_encodings = tokenize_data(train_texts)

val_encodings = tokenize_data(val_texts)

return train_encodings, val_encodings, train_labels.tolist(), val_labels.tolist()
