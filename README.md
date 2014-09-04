To set clone everything do this:

<pre>
mkdir taskcluster
cd taskcluster
curl -L https://storage.googleapis.com/git-repo-downloads/repo > repo
chmod +x repo
./repo init -u http://github.com/jhford/taskcluster-manifest
./repo sync
</pre>
