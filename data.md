..\cv_venv\Scripts\activate

print(tf.test.is_built_with_cuda())
print(tf.config.list_physical_devices('GPU'))
