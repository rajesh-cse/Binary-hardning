# Binary-hardning
Code tamper-proofing through binary hardning
Terminal 1
run python monitor.py dbg_injected

Terminal 2
echo '' > verify_dbg_injected.txt
run ./dbg_injected < in > out

Terminal 3
watch -n 0.3 cat verify_dbg_injected.txt
