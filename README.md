# Network Stream Transport
The report of this project is written in Greek

<p>This project focuses on <strong>Large-Scale Data Network Transport</strong>, analyzing packet exchange processes within a defined network topology. The simulations and experiments are implemented in Python, with corresponding visual data presented in histograms.</p>

<h2><strong>Network Topology</strong></h2>
    <ul>
        <li>The network topology is designed and implemented in the provided Python script.</li>
        <li>Visual representation includes host and switch connections, detailing the network structure.</li>
    </ul>

<h2><strong>Experiment 1: Packet Exchange between h1 and h11</strong></h2>
    <ul>
        <li>Initial routing paths were configured through forwarding rules.</li>
        <li>Results after packet transmission and return were documented, including delay and jitter metrics.</li>
        <li>Routing paths were modified to observe the impact on transmission times.</li>
        <li><strong>Key Findings:</strong>
            <ul>
                <li>Improved transmission times with the new route.</li>
                <li>No packet loss observed in any routing configuration.</li>
            </ul>
        </li>
    </ul>

<h2><strong>Experiment 2: Packet Exchange between h1 and h4</strong></h2>
    <ul>
        <li>Repetition of the procedure with new host endpoints (h1 to h4).</li>
        <li>Analysis of initial and altered routing paths.</li>
        <li>Comparison of transmission delays and bitrates post-routing adjustments.</li>
        <li><strong>Key Findings:</strong>
            <ul>
                <li>Significant changes in transmission performance based on routing paths.</li>
                <li>Consistency in packet integrity with zero loss detected.</li>
            </ul>
        </li>
    </ul>

<h2><strong>Data Visualization</strong></h2>
    <p>Histograms for <strong>Delay Jitter</strong> and <strong>Bitrate</strong> are generated using data from <code>combined_stats_1st.data</code>, visualized in Excel.</p>
