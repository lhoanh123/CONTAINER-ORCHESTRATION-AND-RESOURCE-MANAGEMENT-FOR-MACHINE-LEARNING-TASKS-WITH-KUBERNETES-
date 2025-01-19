# CONTAINER-ORCHESTRATION-AND-RESOURCE-MANAGEMENT-FOR-MACHINE-LEARNING-TASKS-WITH-KUBERNETES

## BÁO CÁO ĐỒ ÁN CHUYÊN NGÀNH
**ĐIỀU PHỐI CONTAINER VÀ QUẢN LÝ TÀI NGUYÊN CHO CÁC TÁC VỤ HỌC MÁY VỚI KUBERNETES**  
**CONTAINER ORCHESTRATION AND RESOURCE MANAGEMENT FOR MACHINE LEARNING TASKS WITH KUBERNETES**

## Thông Tin Dự Án

Dự án này nghiên cứu và triển khai việc quản lý container và tài nguyên trong môi trường Kubernetes cho các tác vụ học máy (machine learning). Mục tiêu chính là tối ưu hóa quá trình triển khai, mở rộng, và quản lý tài nguyên cho các ứng dụng học máy trong môi trường container hóa, sử dụng Kubernetes làm công cụ quản lý container và tài nguyên.

### Các Thành Phần Chính Của Dự Án:
- **Kubernetes**: Hệ thống điều phối container, giúp tự động hóa việc triển khai, quản lý và mở rộng các ứng dụng container.
- **Rancher**: Công cụ quản lý Kubernetes với giao diện người dùng dễ sử dụng và tích hợp nhiều tính năng cho quản lý cluster.
- **Longhorn**: Hệ thống lưu trữ phân tán, giúp quản lý dữ liệu trong môi trường Kubernetes.
- **Prometheus + Grafana**: Bộ công cụ giám sát và quan sát hiệu suất hệ thống.
- **MinIO**: Dịch vụ lưu trữ đối tượng tương tự như AWS S3.
- **MLflow**: Nền tảng mã nguồn mở cho quản lý vòng đời mô hình học máy.
- **JupyterHub**: Hệ thống cho phép người dùng chạy và chia sẻ notebooks Jupyter trong môi trường Kubernetes.
- **Ansible**: Công cụ tự động hóa cấu hình và triển khai, sử dụng Ansible để tự động hóa các tác vụ như cài đặt Kubernetes, Rancher, và các công cụ hỗ trợ.

## Mục Tiêu Dự Án

1. **Triển khai Kubernetes với HA (High Availability)** cho các node master.
2. **Cài đặt và cấu hình Rancher** để quản lý cluster Kubernetes.
3. **Quản lý tài nguyên** trong Kubernetes với các công cụ như HPA, VPA và các tính năng tự động mở rộng.
4. **Cài đặt các công cụ học máy** như MLflow, JupyterHub, và MinIO trong Kubernetes.
5. **Giám sát và quan sát** hệ thống với Prometheus và Grafana.
6. **Quản lý lưu trữ phân tán** với Longhorn.
7. **Tự động hóa triển khai và cấu hình** sử dụng Ansible, giúp giảm thiểu công sức thủ công và tăng tính nhất quán trong các môi trường khác nhau.

## Thành Viên Nhóm
- **LÊ HOÀNG OANH** - 21521253
- **NGUYỄN BÌNH KHẢI** - 21522184
