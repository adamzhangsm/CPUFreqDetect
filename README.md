# CPUFreqDetector
A sample program for Azure VM to monitor CPU frequency in the runtime.

- This x64 sample program is based on this Github Repo:
https://github.com/google/UIforETW/blob/main/UIforETW/CPUFrequency.cpp#L67

- This sample program is for demonstration purpose only. It's NOT recommended to use the output of this sample program to evaluate VM performance or adjust VM workload. 

- The core frequency reported by this sample program is not real frequency of physical CPU core. It shows the executing efficiency for a specific group of instructions [SpinALot](https://github.com/google/UIforETW/blob/main/UIforETW/SpinALot64.asm) routine on each core. But it's sufficient to prove Turbo Boosting is working in Azure VM.

- For Windows Server 2019 Only.
