suricatac
=========

A suricata unix socket client in PERL

Usage
-----

Start it from command line and issue commands. Command options need to be passed as
named argument:

    # suricatac.pl
    >>> pcap-file filename=/home/eric/git/oisf/benches/sandnet.pcap output-dir=/tmp/
    $VAR1 = {
              'message' => 'Successfully added file to list',
              'return' => 'OK'
            };
    >>> pcap-file-list
    $VAR1 = {
              'message' => {
                             'count' => 0,
                             'files' => []
                           },
              'return' => 'OK'
            };
