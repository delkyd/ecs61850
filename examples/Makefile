
EXAMPLE_DIRS = mms_client_example1
EXAMPLE_DIRS += mms_client_example2
EXAMPLE_DIRS += mms_client_example3 
EXAMPLE_DIRS += mms_client_example4
EXAMPLE_DIRS += mms_client_example_reporting
EXAMPLE_DIRS += iec61850_client_example1
EXAMPLE_DIRS += iec61850_client_example2
EXAMPLE_DIRS += server_example1
EXAMPLE_DIRS += server_example2
EXAMPLE_DIRS += server_example3
EXAMPLE_DIRS += server_example4
EXAMPLE_DIRS += server_example5
EXAMPLE_DIRS += server_example_goose
EXAMPLE_DIRS += goose_subscriber
EXAMPLE_DIRS += mms_utility

all:	examples

examples:
	-for d in $(EXAMPLE_DIRS); do(cd $$d; $(MAKE)); done

clean:
	-for d in $(EXAMPLE_DIRS); do(cd $$d; $(MAKE) clean); done
	
