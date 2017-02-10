<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [1.1 - 2.2 主要定义、定理备忘录](#11-22-主要定义定理备忘录)
	- [1.1 Introduction](#11-introduction)
	- [1.2 Vector Space](#12-vector-space)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)
	- [1.3 Subspace](#13-subspace)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)
	- [1.4 Linear Combinations and Systems of Linear Equations](#14-linear-combinations-and-systems-of-linear-equations)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)
	- [1.5 Linear Dependence and Linear Independence](#15-linear-dependence-and-linear-independence)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)
	- [1.6 Bases and Dimension](#16-bases-and-dimension)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)
	- [2.1 Linear Transformations, Null Spaces and Ranges](#21-linear-transformations-null-spaces-and-ranges)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)
	- [2.2 The Matrix Representation of A Linear Transformation](#22-the-matrix-representation-of-a-linear-transformation)
		- [Definitions](#definitions)
		- [Theorem](#theorem)
		- [Corollary](#corollary)

<!-- /TOC -->

# 1.1 - 2.2 主要定义、定理备忘录
---

## 1.1 Introduction

略

---
## 1.2 Vector Space

### Definitions

* Vector Space `(P18)`

### Theorem

* 1.1. Vector 加法消去律 `(P23)`
* 1.2. 有关 $\vec{0}$ Vector 的性质 `(P24)`

### Corollary

* 1\. Vector Space 中 $\vec{0}$ Vector 是唯一的 `(P23)`
* 2\. Vector Space 中 任何向量都是唯一的 `(P24)`
---
## 1.3 Subspace

### Definitions

* subspace `(P28)`

### Theorem

* 1.3. Subspace 的 充分必要条件 `(P29)`
* 1.4. Subspace 的 交集也是 Subspace `(P31)`

### Corollary

---
## 1.4 Linear Combinations and Systems of Linear Equations

### Definitions

* Linear Combination `(P36)`
* span `P(42)`
* spans (generates) `(P42)`

### Theorem

* 1.5. Vector Space 任何一个 Subset 的 span 都是这个 Space 的 Subspace，并且 Vector Space 如果包含这个 Subset 那么一定包含这个 Subset 的 Span `(P42)`

### Corollary

---
## 1.5 Linear Dependence and Linear Independence

### Definitions

* Linearly Dependent `(P48)`
* Linearly Independent `(P49)`

### Theorem

* 1.6. $V$ 是一个 Vector Space 并且 $S_1 \subseteq S_2 \subseteq V$ ，如果 $S_1$ 是 linearly dependent 那么 $S_2$ 也是 `(P51)`
* 1.7. $S$ 是 Vector Space $V$ 的一个 linearly independent subset 并且有一个 vector $\vec{v}$ 在 $V$ 但是不在 $S$ 里面，那么 $S \cup{\{\vec{v}\}}$ 是 linearly dependent 当且仅当 $\vec{v} \in span(S)$ `(P51)`

### Corollary

* 1\. $V$ 是一个 Vector Space 并且 $S_1 \subseteq S_2 \subseteq V$ ，如果 $S_2$ 是 linearly independent 那么 $S_1$ 也是 `(P51)`

---
## 1.6 Bases and Dimension

### Definitions

* basis `(P55)`
* Dimension `(P58-P59)`

### Theorem

* 1.8. basis 成立的条件 `(P55)`
* 1.9. vector space 有 finite basis 的条件 `(P56)`
* 1.10. Replacement Theorem 替代定理 `(P57)`
* 1.11. Subspace 和 Vector Space 维数的关系 `(P62)`


### Corollary

* 1\. basis 数量都相同 `(P58)`
* 2\. N-dimension Vector Space 性质 `(P59-P60)`
* 3\. Subspace 的 basis和 Vector Space 的 basis 的关系 `(P63)`


---
## 2.1 Linear Transformations, Null Spaces and Ranges

### Definitions

* Linear Transformation Form `(P77)`
* Null Space (Kernel) `(P79)`
* Range (Image) `(P79)`
* Nullity `(P81)`
* Rank `(P81)`

### Theorem

* 2.1. $N(T)$ 和 $R(T)$ 都是 subspace `(P80)`
* 2.2. $R(T)$ 和 $V$ 的 basis 的关系 `(P80)`
* 2.3. Dimension Theorem `(P82)`
* 2.4. 一个 $T$ 是 one-to-one 的条件 `(P83)`
* 2.5. 一个 $T$ 是 linear 的等价说法 `(P83)`
* 2.6. 一个 $V$ 的 basis 都可以被正好一个 $T$ 成 $W$ 里面的对应的值 `(P84)`


### Corollary

* 1\. 两个 Transformation 相等的条件 `(P85)`

---
## 2.2 The Matrix Representation of A Linear Transformation

### Definitions

* ordered basis `(P91)`
* standard ordered basis `(P91)`
* coordinate vector `(P92)`
* matrix representation of $T$ in the ordered bases `(P92)`
* Transformation Addition `(P94)`
* Transformation scalar multiplication `(P94)`
* $\mathcal{L}(V,W)$ `(P94)`

### Theorem

* 2.7. 两个 Transformation 相加后 加法和数乘性质 `(P94)`
* 2.8. 两个 Transformation 运算之后的 coordinate 的关系 `(P94)`

### Corollary
