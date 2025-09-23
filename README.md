We consider a federated reinforcement learning setting involving $M$ agents, all of whom interact with a common Markov Decision Process (MDP). The agents exchange information via a central server to learn the optimal value function. Our goal is to understand to what extent one can hope for collaborative sample-complexity speedups in such a setting, when a small fraction of the agents are adversarial and can act arbitrarily. To that end, we propose 𝚁𝚘𝚋𝚞𝚜𝚝 𝙵𝚎𝚍-𝚀, a federated Q-learning algorithm that blends ideas from both model-based and model-free RL, along with the median-of-means device from robust statistics. We prove that with high-probability, 𝚁𝚘𝚋𝚞𝚜𝚝 𝙵𝚎𝚍-𝚀 (i) guarantees \emph{exact} convergence to the optimal value function in the limit of infinite samples, despite corruption, and (ii) enjoys near-optimal finite-time rates that benefit from collaboration. Perhaps surprisingly, our approach requires just $\tilde{O}(1)$ rounds of communication to achieve each of the above guarantees, a feature of independent interest in FL where communication is the major bottleneck.
<table>
<tr>
  <td>
    <img src="https://github.com/sreejeetm1729/Robust-Federated-Q-Learning-with-Almost-No-communication/blob/main/Robust%20Fed-Q%20Animated%20corruption.gif" style="width:250px">
    <img src="https://github.com/sreejeetm1729/Robust-Federated-Q-Learning-with-Almost-No-communication/blob/main/Figure%202%20Robust%20Fed%20Q%20with%20corruption%20fraction%200.01.png" style="width:250px">
    <img src="https://github.com/sreejeetm1729/Robust-Federated-Q-Learning-with-Almost-No-communication/blob/main/Figure%201%20Robust%20Fed%20Q%20with%20corruption%20fraction%200.01%20(3).png" style="width:250px">
 </td>
</tr>
