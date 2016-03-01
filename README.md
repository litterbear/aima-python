# aima-python

Python code for the book  [Artificial Intelligence - A Modern Approach 3rd Edition](http://aima.cs.berkeley.edu/)

Eventually, this repository should have code for everything in the book.

What languages are instructors recommending?  To get an approximate
idea, I gave the query <tt>norvig russell "Modern Approach"</tt> along with
the names of various languages and looked at the estimated counts of results on
various dates. However, I don't have much confidence in these figures...

<p>
<table border=1>
<tr><th>Language<th>Sep 2004<th>Feb 2005<th>Jun 2007<th>Jan 2010<th>Feb 2016
<tr><td> <a href="http://www.google.com/search?q=norvig+russell+%22Modern+Approach%22"> <i>none</i></a><td align=right> 8,080<td align=right>20,100<td align=right>75,200<td align=right>150,000<td align=right>132,000
<tr><td> <a href="http://www.google.com/search?q=java+norvig+russell+%22Modern+Approach%22">java   </a><td align=right> 1,990<td align=right>4,930<td align=right>44,200<td align=right>37,000<td align=right>50,000
<tr><td> <a href="http://www.google.com/search?q=c%2B%2B+norvig+russell+%22Modern+Approach%22">c++    </a><td align=right>  875<td align=right>1,820<td align=right>35,300<td align=right>105,000<td align=right>35,000
<tr><td> <a href="http://www.google.com/search?q=lisp+norvig+russell+%22Modern+Approach%22">lisp   </a><td align=right>  844<td align=right>974<td align=right>30,100<td align=right>19,000<td align=right>14,000
<tr><td> <a href="http://www.google.com/search?q=prolog+norvig+russell+%22Modern+Approach%22">prolog </a><td align=right>  789<td align=right>2,010<td align=right>23,200<td align=right>17,000<td align=right>16,000
<tr><td> <a href="http://www.google.com/search?q=python+norvig+russell+%22Modern+Approach%22">python </a><td align=right>  785<td align=right>1,240<td align=right>18,400<td align=right>11,000<td align=right>12,000

</table>

[Environment](/agents.py)

### Index of Implemented Algorithms
<table style="width:100%">
   <tbody>
   <tr>
       <td><b>Fig</b></td>
       <td><b>Page</b></td>
       <td><b>Name (in book)</b></td>
       <td><b>Code</b></td>
   </tr>
   <tr>
       <td>2</td>
       <td>34</td>
       <td>Environment</td>
       <td> [Environment](/agents.py) </td>
   </tr>
   <tr>
       <td>2.1</td>
       <td>35</td>
       <td>Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/Agent.java">Agent</a></td>
   </tr>
   <tr>
       <td>2.3</td>
       <td>36</td>
       <td>Table-Driven-Vacuum-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/vacuum/TableDrivenVacuumAgent.java">TableDrivenVacuumAgent</a></td>
   </tr>
   <tr>
       <td>2.7</td>
       <td>47</td>
       <td>Table-Driven-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/impl/aprog/TableDrivenAgentProgram.java">TableDrivenAgentProgram</a></td>
   </tr>
   <tr>
       <td>2.8</td>
       <td>48</td>
       <td>Reflex-Vacuum-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/vacuum/ReflexVacuumAgent.java">ReflexVacuumAgent</a></td>
   </tr>
   <tr>
       <td>2.10</td>
       <td>49</td>
       <td>Simple-Reflex-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/impl/aprog/SimpleReflexAgentProgram.java">SimpleReflexAgentProgram</a></td>
   </tr>
   <tr>
       <td>2.12</td>
       <td>51</td>
       <td>Model-Based-Reflex-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/agent/impl/aprog/ModelBasedReflexAgentProgram.java">ModelBasedReflexAgentProgram</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>66</td>
       <td>Problem</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/Problem.java">Problem</a></td>
   </tr>
   <tr>
       <td>3.1</td>
       <td>67</td>
       <td>Simple-Problem-Solving-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/SimpleProblemSolvingAgent.java">SimpleProblemSolvingAgent</a></td>
   </tr>
   <tr>
       <td>3.2</td>
       <td>68</td>
       <td>Romania</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/map/SimplifiedRoadMapOfPartOfRomania.java">SimplifiedRoadMapOfPartOfRomania</a></td>
   </tr>
   <tr>
       <td>3.7</td>
       <td>77</td>
       <td>Tree-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/TreeSearch.java">TreeSearch</a></td>
   </tr>
   <tr>
       <td>3.7</td>
       <td>77</td>
       <td>Graph-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/GraphSearch.java">GraphSearch</a></td>
   </tr>
   <tr>
       <td>3.10</td>
       <td>79</td>
       <td>Node</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/framework/Node.java">Node</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>79</td>
       <td>Queue</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/util/datastructure/Queue.java">Queue</a></td>
   </tr>
   <tr>
       <td>3.11</td>
       <td>82</td>
       <td>Breadth-First-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/BreadthFirstSearch.java">BreadthFirstSearch</a></td>
   </tr>
   <tr>
       <td>3.14</td>
       <td>84</td>
       <td>Uniform-Cost-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/UniformCostSearch.java">UniformCostSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>85</td>
       <td>Depth-first Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/DepthFirstSearch.java">DepthFirstSearch</a></td>
   </tr>
   <tr>
       <td>3.17</td>
       <td>88</td>
       <td>Depth-Limited-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/DepthLimitedSearch.java">DepthLimitedSearch</a></td>
   </tr>
   <tr>
       <td>3.18</td>
       <td>89</td>
       <td>Iterative-Deepening-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/IterativeDeepeningSearch.java">IterativeDeepeningSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>90</td>
       <td>Bidirectional search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/uninformed/BidirectionalSearch.java">BidirectionalSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>92</td>
       <td>Best-First search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/BestFirstSearch.java">BestFirstSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>92</td>
       <td>Greedy best-First search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/GreedyBestFirstSearch.java">GreedyBestFirstSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>93</td>
       <td>A* Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/AStarSearch.java">AStarSearch</a></td>
   </tr>
   <tr>
       <td>3.26</td>
       <td>99</td>
       <td>Recursive-Best-First-Search </td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/informed/RecursiveBestFirstSearch.java">RecursiveBestFirstSearch</a></td>
   </tr>
   <tr>
       <td>4.2</td>
       <td>122</td>
       <td>Hill-Climbing</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/local/HillClimbingSearch.java">HillClimbingSearch</a></td>
   </tr>
   <tr>
       <td>4.5</td>
       <td>126</td>
       <td>Simulated-Annealing</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/local/SimulatedAnnealingSearch.java">SimulatedAnnealingSearch</a></td>
   </tr>
   <tr>
       <td>4.8</td>
       <td>129</td>
       <td>Genetic-Algorithm</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/local/GeneticAlgorithm.java">GeneticAlgorithm</a></td>
   </tr>
   <tr>
       <td>4.11</td>
       <td>136</td>
       <td>And-Or-Graph-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/nondeterministic/AndOrSearch.java">AndOrSearch</a></td>
   </tr>
   <tr>
       <td>4</td>
       <td>147</td>
       <td>Online search problem</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/online/OnlineSearchProblem.java">OnlineSearchProblem</a></td>
   </tr>
   <tr>
       <td>4.21</td>
       <td>150</td>
       <td>Online-DFS-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/online/OnlineDFSAgent.java">OnlineDFSAgent</a></td>
   </tr>
   <tr>
       <td>4.24</td>
       <td>152</td>
       <td>LRTA*-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/online/LRTAStarAgent.java">LRTAStarAgent</a></td>
   </tr>
   <tr>
       <td>5.3</td>
       <td>166</td>
       <td>Minimax-Decision</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/adversarial/MinimaxSearch.java">MinimaxSearch</a></td>
   </tr>
   <tr>
       <td>5.7</td>
       <td>170</td>
       <td>Alpha-Beta-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/adversarial/AlphaBetaSearch.java">AlphaBetaSearch</a></td>
   </tr>
   <tr>
       <td>6</td>
       <td>202</td>
       <td>CSP</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/CSP.java">CSP</a></td>
   </tr>
   <tr>
       <td>6.1</td>
       <td>204</td>
       <td>Map CSP</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/MapCSP.java">MapCSP</a></td>
   </tr>
   <tr>
       <td>6.3</td>
       <td>209</td>
       <td>AC-3</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/AC3Strategy.java">AC3Strategy</a></td>
   </tr>
   <tr>
       <td>6.5</td>
       <td>215</td>
       <td>Backtracking-Search</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/BacktrackingStrategy.java">BacktrackingStrategy</a></td>
   </tr>
   <tr>
       <td>6.8</td>
       <td>221</td>
       <td>Min-Conflicts</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/search/csp/MinConflictsStrategy.java">MinConflictsStrategy</a></td>
   </tr>
   <tr>
       <td>6.11</td>
       <td>209</td>
       <td>Tree-CSP-Solver</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>7</td>
       <td>235</td>
       <td>Knowledge Base</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/kb/KnowledgeBase.java">KnowledgeBase</a></td>
   </tr>
   <tr>
       <td>7.1</td>
       <td>236</td>
       <td>KB-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/agent/KBAgent.java">KBAgent</a></td>
   </tr>
   <tr>
       <td>7.7</td>
       <td>244</td>
       <td>Propositional-Logic-Sentence</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/parsing/ast/Sentence.java">Sentence</a></td>
   </tr>
   <tr>
       <td>7.10</td>
       <td>248</td>
       <td>TT-Entails</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/TTEntails.java">TTEntails</a></td>
   </tr>
   <tr>
       <td>7</td>
       <td>253</td>
       <td>Convert-to-CNF</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/visitors/ConvertToCNF.java">ConvertToCNF</a></td>
   </tr>
   <tr>
       <td>7.12</td>
       <td>255</td>
       <td>PL-Resolution</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/PLResolution.java">PLResolution</a></td>
   </tr>
   <tr>
       <td>7.15</td>
       <td>258</td>
       <td>PL-FC-Entails?</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/PLFCEntails.java">PLFCEntails</a></td>
   </tr>
   <tr>
       <td>7.17</td>
       <td>261</td>
       <td>DPLL-Satisfiable?</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/DPLLSatisfiable.java">DPLLSatisfiable</a></td>
   </tr>
   <tr>
       <td>7.18</td>
       <td>263</td>
       <td>WalkSAT</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/WalkSAT.java">WalkSAT</a></td>
   </tr>
   <tr>
       <td>7.20</td>
       <td>270</td>
       <td>Hybrid-Wumpus-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/environment/wumpusworld/HybridWumpusAgent.java">HybridWumpusAgent</a></td>
   </tr>
   <tr>
       <td>7.22</td>
       <td>272</td>
       <td>SATPlan</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/propositional/inference/SATPlan.java">SATPlan</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>323</td>
       <td>Subst</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/SubstVisitor.java">SubstVisitor</a></td>
   </tr>
   <tr>
       <td>9.1</td>
       <td>328</td>
       <td>Unify</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/Unifier.java">Unifier</a></td>
   </tr>
   <tr>
       <td>9.3</td>
       <td>332</td>
       <td>FOL-FC-Ask</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/FOLFCAsk.java">FOLFCAsk</a></td>
   </tr>
   <tr>
       <td>9.3</td>
       <td>332</td>
       <td>FOL-BC-Ask</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/FOLBCAsk.java">FOLBCAsk</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>345</td>
       <td>CNF</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/CNFConverter.java">CNFConverter</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>347</td>
       <td>Resolution</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/FOLTFMResolution.java">FOLTFMResolution</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>354</td>
       <td>Demodulation</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/Demodulation.java">Demodulation</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>354</td>
       <td>Paramodulation</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/inference/Paramodulation.java">Paramodulation</a></td>
   </tr>
   <tr>
       <td>9</td>
       <td>345</td>
       <td>Subsumption</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/logic/fol/SubsumptionElimination.java">SubsumptionElimination</a></td>
   </tr>
   <tr>
       <td>10.9</td>
       <td>383</td>
       <td>Graphplan</td>
       <td>---</td>
   </tr>
   <tr>
       <td>11.5</td>
       <td>409</td>
       <td>Hierarchical-Search</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>11.8</td>
       <td>414</td>
       <td>Angelic-Search</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>13.1</td>
       <td>484</td>
       <td>DT-Agent</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>13</td>
       <td>484</td>
       <td>Probability-Model</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/ProbabilityModel.java">ProbabilityModel</a></td>
   </tr>
   <tr>
       <td>13</td>
       <td>487</td>
       <td>Probability-Distribution</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/ProbabilityDistribution.java">ProbabilityDistribution</a></td>
   </tr>
   <tr>
       <td>13</td>
       <td>490</td>
       <td>Full-Joint-Distribution</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/full/FullJointDistributionModel.java">FullJointDistributionModel</a></td>
   </tr>
   <tr>
       <td>14</td>
       <td>510</td>
       <td>Bayesian Network</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/BayesianNetwork.java">BayesianNetwork</a></td>
   </tr>
   <tr>
       <td>14.9</td>
       <td>525</td>
       <td>Enumeration-Ask</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/exact/EnumerationAsk.java">EnumerationAsk</a></td>
   </tr>
   <tr>
       <td>14.11</td>
       <td>528</td>
       <td>Elimination-Ask</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/exact/EliminationAsk.java">EliminationAsk</a></td>
   </tr>
   <tr>
       <td>14.13</td>
       <td>531</td>
       <td>Prior-Sample</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/approx/PriorSample.java">PriorSample</a></td>
   </tr>
   <tr>
       <td>14.14</td>
       <td>533</td>
       <td>Rejection-Sampling</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/approx/RejectionSampling.java">RejectionSampling</a></td>
   </tr>
   <tr>
       <td>14.15</td>
       <td>534</td>
       <td>Likelihood-Weighting</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/approx/LikelihoodWeighting.java">LikelihoodWeighting</a></td>
   </tr>
   <tr>
       <td>14.16</td>
       <td>537</td>
       <td>GIBBS-Ask</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/approx/GibbsAsk.java">GibbsAsk</a></td>
   </tr>
   <tr>
       <td>15.4</td>
       <td>576</td>
       <td>Forward-Backward</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/temporal/generic/ForwardBackward.java">ForwardBackward</a></td>
   </tr>
   <tr>
       <td>15</td>
       <td>578</td>
       <td>Hidden Markov Model</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/hmm/HiddenMarkovModel.java">HiddenMarkovModel</a></td>
   </tr>
   <tr>
       <td>15.6</td>
       <td>580</td>
       <td>Fixed-Lag-Smoothing</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/hmm/exact/FixedLagSmoothing.java">FixedLagSmoothing</a></td>
   </tr>
   <tr>
       <td>15</td>
       <td>590</td>
       <td>Dynamic Bayesian Network</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/DynamicBayesianNetwork.java">DynamicBayesianNetwork</a></td>
   </tr>
   <tr>
       <td>15.17</td>
       <td>598</td>
       <td>Particle-Filtering</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/bayes/approx/ParticleFiltering.java">ParticleFiltering</a></td>
   </tr>
   <tr>
       <td>16.9</td>
       <td>632</td>
       <td>Information-Gathering-Agent</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>17</td>
       <td>647</td>
       <td>Markov Decision Process</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/mdp/MarkovDecisionProcess.java">MarkovDecisionProcess</a></td>
   </tr>
   <tr>
       <td>17.4</td>
       <td>653</td>
       <td>Value-Iteration</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/mdp/search/ValueIteration.java">ValueIteration</a></td>
   </tr>
   <tr>
       <td>17.7</td>
       <td>657</td>
       <td>Policy-Iteration</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/probability/mdp/search/PolicyIteration.java">PolicyIteration</a></td>
   </tr>
   <tr>
       <td>17.9</td>
       <td>663</td>
       <td>POMDP-Value-Iteration</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>18.5</td>
       <td>702</td>
       <td>Decision-Tree-Learning</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/learners/DecisionTreeLearner.java">DecisionTreeLearner</a></td>
   </tr>
   <tr>
       <td>18.8</td>
       <td>710</td>
       <td>Cross-Validation-Wrapper</td>
       <td>---</a></td>
   </tr>
   <tr>
       <td>18.11</td>
       <td>717</td>
       <td>Decision-List-Learning</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/learners/DecisionListLearner.java">DecisionListLearner</a></td>
   </tr>
   <tr>
       <td>18.24</td>
       <td>734</td>
       <td>Back-Prop-Learning</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/neural/BackPropLearning.java">BackPropLearning</a></td>
   </tr>
   <tr>
       <td>18.34</td>
       <td>751</td>
       <td>AdaBoost</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/learners/AdaBoostLearner.java">AdaBoostLearner</a></td>
   </tr>
   <tr>
       <td>19.2</td>
       <td>771</td>
       <td>Current-Best-Learning</td>
       <td>---</td>
   </tr>
   <tr>
       <td>19.3</td>
       <td>773</td>
       <td>Version-Space-Learning</td>
       <td>---</td>
   </tr>
   <tr>
       <td>19.8</td>
       <td>786</td>
       <td>Minimal-Consistent-Det</td>
       <td>---</td>
   </tr>
   <tr>
       <td>19.12</td>
       <td>793</td>
       <td>FOIL</td>
       <td>---</td>
   </tr>
   <tr>
       <td>21.2</td>
       <td>834</td>
       <td>Passive-ADP-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/reinforcement/agent/PassiveADPAgent.java">PassiveADPAgent</a></td>
   </tr>
   <tr>
       <td>21.4</td>
       <td>837</td>
       <td>Passive-TD-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/reinforcement/agent/PassiveTDAgent.java">PassiveTDAgent</a></td>
   </tr>
   <tr>
       <td>21.8</td>
       <td>844</td>
       <td>Q-Learning-Agent</td>
       <td><a href="https://github.com/aimacode/aima-java/blob/AIMA3e/aima-core/src/main/java/aima/core/learning/reinforcement/agent/QLearningAgent.java">QLearningAgent</a></td>
   </tr>
   <tr>
       <td>22.1</td>
       <td>871</td>
       <td>HITS</td>
       <td>---</td>
   </tr>
   <tr>
       <td>23.5</td>
       <td>894</td>
       <td>CYK-Parse</td>
       <td>---</td>
   </tr>
   <tr>
       <td>25.9</td>
       <td>982</td>
       <td>Monte-Carlo-Localization</td>
       <td>---</td>
   </tr>
   </tbody>
</table>
