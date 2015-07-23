# rpm-activemq

An RPM spec file to install the is Apache ActiveMQ open source message broker.

To Build:

    sudo yum -y groupinstall "Development Tools"
    wget -P ~/rpmbuild/SOURCES/ http://mirror.ox.ac.uk/sites/rsync.apache.org/activemq/5.11.1/apache-activemq-5.11.1-bin.tar.gz
    rpmbuild -bb  ~/rpmbuild/SPECS/activemq.spec --define "release 1"

