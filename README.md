<h1>Keys and Values Explained</h1>
<ol>
    <li><h2>hosts</h2>: Defines the target hosts.</li>
    <li><h2>user</h2>: Specifies the user for SSH connection.</li>
    <li><h2>become</h2>: Enables privilege escalation.</li>
    <li><h2>tasks</h2>: Lists the tasks to execute.</li>
    <li><h2>name</h2>: Describes each task.</li>
    <li><h2>yum</h2>: Manages packages with YUM.</li>
    <li><h2>state</h2>: Specifies the desired state of the package (e.g., latest).</li>
    <li><h2>script</h2>: Runs a script on the remote host.</li>
    <li><h2>args</h2>: Additional arguments for the script.</li>
    <li><h2>ignore_errors</h2>: Continues playbook execution even if an error occurs.</li>
    <li><h2>register</h2>: Saves the output of a task.</li>
    <li><h2>debug</h2>: Prints variable content for debugging purposes.</li>
    <li><h2>fail</h2>: Stops the playbook with an error message.</li>
    <li><h2>when</h2>: Conditional statement to control task execution.</li>
    <li><h2>shell</h2>: Executes shell commands.</li>
    <li><h2>command</h2>: Runs system commands.</li>
    <li><h2>async</h2>: Runs commands asynchronously.</li>
    <li><h2>poll</h2>: Controls polling behavior for asynchronous tasks.</li>
    <li><h2>pause</h2>: Pauses playbook execution.</li>
    <li><h2>local_action</h2>: Executes a task locally on the control machine.</li>
    <li><h2>until</h2>: Repeats a task until a condition is met.</li>
    <li><h2>retries</h2>: Specifies the number of retries.</li>
    <li><h2>delay</h2>: Wait time between retries.</li>
</ol>
