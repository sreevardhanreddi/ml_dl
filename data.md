..\cv_venv\Scripts\activate

print(tf.test.is_built_with_cuda())
print(tf.config.list_physical_devices('GPU'))

```
with tf.device('/cpu:0'):
    pass

with tf.device('/gpu:0'):
    pass
```
