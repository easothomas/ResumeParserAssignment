Resume Project: Resume Parser

1. To get the latest code, please clone git repository.
git clone https://github.com/RohitDas/ResumeParserAssignment.git

2. To install all dependencies, please run following command.
sh INSTALL.sh

3. Please modify config.ini in Config directory to point to right paths.

4. To run unit test, modify paths in UnitTest.py and run following commands.
python UnitTest.py

You can also parse multiple files in batch mode by uncommenting/commenting relevant lines.

5. To run parser as SOAP service, run following command in src directory.
python resume_parser_server.py


6. INSTALL pdf2json.
   a. wget https://pdf2json.googlecode.com/files/pdf2json-0.68.tar.gz
   b. tar xzvf pdf2json-0.68.tar.gz -C /tmp/pdf2jsonsource
   c. cd /tmp/pdf2jsonsource;
   d.  ./configure
   e. sudo make
   f. sudo make install

7. INSTALL ABIWORD.
   sudo apt-get install abiword


