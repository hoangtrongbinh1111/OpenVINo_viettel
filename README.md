
- Tải các model pretrained(Caffe, Kaldi, tf,...)
- Chuyển các mô hình pretrained sang IR:
+Vào thư mục install_prerequisites: chạy câu lệnh ./install_prerequisites.sh để cài đặt các thư viện cần thiết
+Vào thư mục _mo: chạy câu lệnh để chuyển sang IR
python3 mo.py --input_model {DIR_pretrained_model} (--output_dir {DIR_IR} --model_name {IR_name})
- Chạy Inference Engine
+Vào file demos, chạy câu lệnh ./build_demos.sh
+Sau khi build, thư mục nằm ở Release
+ Vào thư mục Release, chạy câu lệnh : 
./interactive_face_detection_demo -m {DIR_IR_*.xml} -i {camera}
