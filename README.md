# SafeBPF patch

## Instruction

Apply the [patch](./SafeBPF.patch) to the mainline Linux kernel v6.3.8.


## Publications

This patch is based on the work published in the two following publications:
- Soo Yee Lim, Tanya Prasad, Xueyuan Han, and Thomas Pasquier. "SafeBPF: Hardware-assisted Defense-in-depth for eBPF Kernel Extensions." Proceedings of the 2024 ACM Cloud Computing Security Workshop. 2024.
- Soo YeeLim, Xueyuan Han, and Thomas Pasquier. "Unleashing unprivileged ebpf potential with dynamic sandboxing." Proceedings of the 1st ACM SIGCOMM Workshop on eBPF and Kernel Extensions. 2023.

```
@inproceedings{soo2024safebpf,
	title = {{SafeBPF: Hardware-assisted Defense-in-depth for eBPF Kernel Extensions}},
	author={Lim, Soo Yee and Prasad, Tanya and Han, Xueyuan and Pasquier, Thomas},
	booktitle={Cloud Computing Security Workshop (CCSW'24)},
	year={2024},
	organization={ACM}
}

@inproceedings{lim2023ebpf,
	title={{Unleashing Unprivileged eBPF Potential with Dynamic Sandboxing}},
	author={Lim, Soo Yee and Han, Xueyuan and Pasquier, Thomas},
	booktitle={SIGCOMM Workshop on eBPF and Kernel Extensions},
	year={2023},
	organization={ACM}
}
```
