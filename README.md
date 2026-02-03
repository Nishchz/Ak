<body>
  <div>
    <h1>🧾Singly LinkedList In Java </h1>
    <p>This repository demostrate the <b> basic operation of a Singly LinkeList</b> implementation in java , It covers adding and removing elements from both ends of the list with clear code</p>
  </div>
  <div>
    <h1>📌 Operation Implemented</h1>
      <h2>➕ Add First</h2>
    <p>Adds a new node at the <b> beginning</b> of the LinkedList</p>
    <h2>🧠 Logic</h2>
    <ul>
      <li>Create a new node</li>
      <li>Points<b> newNode.next</b> to current <b>head</b></li>
      <li>Move <b>head</b> to new node</li>
      <li><mark><b>Time complexity-> O(1)</b></mark></li>
    </ul>
  </div>
  <div>
    <h1>➕Add Last</h1>
    <p>Adds a new node at the <b>end</b> of the LinkedList</p>
    <h2>🧠 Logic</h2>
    <ul>
      <li>Create a new node</li>
      <li>Connect <b>tail.next<b> to new node</li>
      <li>Update <b> tail</b> to new node</li>
      <li><mark><b>Time Complexity->o(1)</li>
    </ul>
  </div>
  <div>
    <h1>⚔️ Remove First</h1> 
    <p>Remove the <b>first node (head) from the LinkedList</b></p>
    <ul>
      <li>Edge case handled </li>
      <li>If list is empty-> print message</li>
      <li>If only one node exists -> set <b>head</b> and <b>tail</b> to <b>null</b></li>
    </ul>
  </div>
  <div>
    <h2>Logic</h2>
    <ul>
      <li>Store <b>head data</b></li>
      <li>Move <b>head</b> to <b>head.next</b></li>
      <li>Decrease size</li>
      <li><mark><b>Time Complexity->O(1)</li>
    </ul>
  </div> <h1>⚔️ Remove Last</h1> 
    <p>Remove the <b>Last node (tail) from the LinkedList</b></p>
  </div>
  <div>
    <h2>Logic</h2>
    <ul>
      <li>Traverse to node at index <b>size-2</b></li>
      <li>Set<b>prev.next=null</b></li>
      <li>Update tail = prev</li>
      <li><mark><b>Time Complexity->O(n)</li>
    </ul>
  </div>
</body>
