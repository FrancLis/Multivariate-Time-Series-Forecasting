### Instructions


load directly the repository using this code

##### Load model
##### loaded_model = tf.keras.models.load_model('./best_model_simple_rnn')
##### loaded_model.summary()
##### assert np.allclose(model_simple_rnn.predict(X_test), loaded_model.predict(X_test))