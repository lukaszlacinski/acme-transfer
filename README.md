# acme-transfer

Download Globus Transfer API and ACME Transfer

    git clone git@github.com:globusonline/transfer-api-client-python.git
    export PYTHONPATH='pwd'/transfer-api-client-python
    git clone git@github.com:lukaszlacinski/acme-transfer.git
    cd acme-transfer

Examples:

    python acme_transfer.py --source-endpoint b4155e9b-6d04-11e5-ba46-22000b92c6ec --source-path /data/test1 \
        --destination-endpoint 693ac576-9237-11e6-b079-22000b92c261 --destination-path /blah/blah/ \
        -c config.json

    python acme_transfer.py --source-endpoint b4155e9b-6d04-11e5-ba46-22000b92c6ec --source-path /data/test1 --source-list list \
        --destination-endpoint 693ac576-9237-11e6-b079-22000b92c261 --destination-path / \
        -c config.json

    python acme_transfer.py --source-endpoint b4155e9b-6d04-11e5-ba46-22000b92c6ec --source-list list \
        --destination-endpoint 693ac576-9237-11e6-b079-22000b92c261 --destination-path / \
        -c config.json

