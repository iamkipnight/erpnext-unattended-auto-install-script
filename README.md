 <strong>1. Clone the Repo:</strong>
<pre><code>git clone https://github.com/flexcomng/erpnext_quick_install.git</code></pre>

<strong>2. Navigate to the folder:</strong>
<pre><code>cd erpnext_quick_install</code></pre>

<strong>3.Make the script executable</strong>
<pre><code>sudo chmod +x erpnext_install.sh</code></pre>

<strong>4.Run the script:</strong>
<pre><code>source erpnext_install.sh</code></pre>

<strong>Compatibility</strong>
Ubuntu 22.04 LTS, Ubuntu 20.04 LTS
Debian 10 (Buster), Debian 11 (Bulls Eye)

<strong>Note:</strong>
Version 15 Compatibility is set to Ubuntu 22.04 LTS and above only. Other Distros or lower Ubuntu versions not supported for version 15 installation. Visit https://onesoftsolutionske.com/how-to-install-erpnext-15-on-ubuntu-22-lts/ to learn how to install ERP Next Step by Step

If you encounter spawn error on socketio when running bench restart, run the following commands:
<pre><code>
bench setup socketio
</code></pre>
<pre><code>bench setup supervisor  </code></pre>
<pre><code>bench setup redis  </code></pre>
<pre><code>sudo supervisorctl reload  </code></pre>
This will fix the spawn error and all services will restart successfully.
