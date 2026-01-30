Day 02 – Linux Architecture, Processes, and systemd
1️⃣ Core components of Linux

Linux is built in layers. At the center is the kernel, which talks directly to the hardware and manages CPU, memory, disks, and networking. Above the kernel is user space, where applications, shells, and system utilities run. To start everything during boot, Linux uses an init system, and on modern systems this is systemd.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6f05bb83-296b-44a3-8078-cca90d068bff" />


2️⃣ How processes are created and managed

Every running program in Linux is a process. A process is usually created when an existing process forks itself and then executes a new program. Each process has a unique PID, consumes CPU and memory, and is managed by the kernel. Linux controls processes using scheduling, priorities, and signals, allowing administrators to start, stop, pause, or monitor them.

3️⃣ What systemd does and why it matters

systemd is the first process started by the kernel (PID 1). It is responsible for booting the system, starting services, managing dependencies, and keeping services running. systemd makes systems more reliable by automatically restarting failed services and providing a standard way to manage logs, services, and system states. For DevOps, systemd is important because most production Linux servers rely on it to manage applications.
