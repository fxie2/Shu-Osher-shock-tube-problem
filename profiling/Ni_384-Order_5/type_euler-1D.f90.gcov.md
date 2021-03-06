### Coverage analysis of *type_euler-1D.f90*

|Metrics|||
| --- | --- | --- |
|Number of executable lines          |266||
|Number of executed lines            |196|74%|
|Number of unexecuted lines          |70|26%|
|Average hits per executed line      |1812675||
|Number of procedures                |28||
|Number of executed procedures       |18|64%|
|Number of unexecuted procedures     |10|36%|
|Average hits per executed procedure |1279889||

 --- 
[![lines](http://www.google.com/chart?cht=p&chs=300x150&chd=s:tQ&chtt=Coverage%20of%20executable%20lines&chdl=Executed%7cUnexecuted&chco=65C1FF|FF9260&chl=74%25%7c26%25)]()
[![procedures](http://www.google.com/chart?cht=p&chs=300x150&chd=s:nW&chtt=Coverage%20of%20procedures&chdl=Executed%7cUnexecuted&chco=65C1FF|FF9260&chl=64%25%7c36%25)]()

#### Unexecuted procedures

 + *function* **euler_local_error**, line 361
 + *function* **euler_multiply_euler**, line 391
 + *function* **output**, line 236
 + *function* **p**, line 937
 + *function* **r**, line 953
 + *function* **real_multiply_euler**, line 452
 + *function* **sub_euler**, line 513
 + *subroutine* **destroy**, line 212
 + *subroutine* **euler_assign_real**, line 588
 + *subroutine* **finalize**, line 874

#### Executed procedures

 + *function* **a**: tested **5170704** times
 + *function* **conservative2primitive**: tested **2838528** times
 + *function* **eigen_vect_L**: tested **2496648** times
 + *function* **eigen_vect_R**: tested **2496648** times
 + *function* **fluxes**: tested **2490180** times
 + *function* **E**: tested **2490180** times
 + *function* **H**: tested **2490180** times
 + *subroutine* **riemann_solver**: tested **1245090** times
 + *subroutine* **compute_inter_states**: tested **1245090** times
 + *subroutine* **euler_assign_euler**: tested **27720** times
 + *function* **euler_multiply_real**: tested **20328** times
 + *function* **add_euler**: tested **12936** times
 + *function* **dEuler_dt**: tested **6468** times
 + *subroutine* **impose_boundary_conditions**: tested **3234** times
 + *subroutine* **reconstruct_interfaces_states**: tested **3234** times
 + *function* **compute_dt**: tested **462** times
 + *function* **primitive2conservative**: tested **384** times
 + *subroutine* **init**: tested **2** times

 --- 
 Report generated by [FoBiS.py](https://github.com/szaghi/FoBiS)