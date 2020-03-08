# savemodel

squeezenet code에서 tf.Session의 그래프를 아래와 같이 저장한다.
tf.train.write_graph(sess.graph_def, './', 'squeeze.pb', as_text=True)

python3 squeezenet_tf.py --in 0000000000.png 이런식으로 실행
(this test squeezenet code is from  avoroshilov /tf-squeezenet)
