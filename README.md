# Switch port Consolidation
This project runs PyATS script to recommend source switch port to target switch port migration and later test the status of port migration. Run "gui.py" to open an interactive GUI and run script accordingly. 
PyAts is used to connect to devices and run different configuration to check switch interfaces, their VLANs and MAC addresses which is used to recommend port migration. Using the GUI, you can send emails, save log files, and view log files generated by the script.

## Execution
To run the project, run the gui.py file
```bash
python gui.py
```
## Testbed sample file
Use csv template in testbed folder to populate source and target switch information

hostname | ip | username | password | protocol | os |
--- | --- | --- | --- |--- |--- |
Switch1 | 192.168.1.1:32576 | cisco | cisco | telnet | ios | 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)