# LinkedList

|  No  | Rules                                                        | Questions         |
| :--: | ------------------------------------------------------------ | ----------------- |
|  1   | Cycle判定: 2stepずつ進むfast pointerと1stepずつ進むslow pointerの衝突判定 | Linked List Cycle |

| Questions                        | 1st  | 2nd  | Note                                                         |
| -------------------------------- | :--: | :--: | ------------------------------------------------------------ |
| Delete Node in a Linked List     |  o   |      | Linked Listの基本で重要                                      |
| Remove Nth Node from End of List |  x   |      | コーナーケースの処理がかなり厄介<br />リストの先頭にdummy nodeを追加してうまいこと処理できる |
| Reverse Linked List              |  x   |      | `tmp = curr.next; curr.next = prev;`としてnextを一旦保存しておくのがポイント |
| Merge Two Sorted Lists           |  x   |      | シンプルな処理または再帰による処理で解ける                   |
| Palindrome Linked List           |  o   |      |                                                              |
| Linked List Cycle                |  o   |      | Cycle判定の基本はやはりfast pointerとslow pointerの衝突判定  |
| Add Two Numbers                  |  o   |      |                                                              |

