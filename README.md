An example demonstrating an issue with ipdb==0.8.1 and behave=1.2.5

# Steps to reproduce

    git clone https://github.com/kowalcj0/behaveipdb.git
    cd behaveipdb
    mkvirtualenv behaveipdb
    pip install -r requirements.txt
    behave

Then when the execution stops at the breakpoint,
try to use regular ipdb commands: `where`, `ls`, `c`, `q` etc
