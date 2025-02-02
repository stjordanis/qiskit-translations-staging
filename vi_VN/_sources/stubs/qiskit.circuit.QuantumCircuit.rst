﻿QuantumCircuit
==============

.. currentmodule:: qiskit.circuit

.. autoclass:: QuantumCircuit
   :no-members:
   :show-inheritance:

   .. rubric:: Methods

   .. autosummary::
      :nosignatures:
      :toctree: ../stubs/

      ~QuantumCircuit.add_bits
      ~QuantumCircuit.add_calibration
      ~QuantumCircuit.add_register
      ~QuantumCircuit.append
      ~QuantumCircuit.assign_parameters
      ~QuantumCircuit.barrier
      ~QuantumCircuit.bind_parameters
      ~QuantumCircuit.break_loop
      ~QuantumCircuit.cast
      ~QuantumCircuit.cbit_argument_conversion
      ~QuantumCircuit.ccx
      ~QuantumCircuit.ch
      ~QuantumCircuit.cls_instances
      ~QuantumCircuit.cls_prefix
      ~QuantumCircuit.cnot
      ~QuantumCircuit.combine
      ~QuantumCircuit.compose
      ~QuantumCircuit.continue_loop
      ~QuantumCircuit.control
      ~QuantumCircuit.copy
      ~QuantumCircuit.count_ops
      ~QuantumCircuit.cp
      ~QuantumCircuit.crx
      ~QuantumCircuit.cry
      ~QuantumCircuit.crz
      ~QuantumCircuit.cswap
      ~QuantumCircuit.csx
      ~QuantumCircuit.cu
      ~QuantumCircuit.cu1
      ~QuantumCircuit.cu3
      ~QuantumCircuit.cx
      ~QuantumCircuit.cy
      ~QuantumCircuit.cz
      ~QuantumCircuit.dcx
      ~QuantumCircuit.decompose
      ~QuantumCircuit.delay
      ~QuantumCircuit.depth
      ~QuantumCircuit.diagonal
      ~QuantumCircuit.draw
      ~QuantumCircuit.ecr
      ~QuantumCircuit.extend
      ~QuantumCircuit.find_bit
      ~QuantumCircuit.for_loop
      ~QuantumCircuit.fredkin
      ~QuantumCircuit.from_qasm_file
      ~QuantumCircuit.from_qasm_str
      ~QuantumCircuit.get_instructions
      ~QuantumCircuit.h
      ~QuantumCircuit.hamiltonian
      ~QuantumCircuit.has_register
      ~QuantumCircuit.i
      ~QuantumCircuit.id
      ~QuantumCircuit.if_else
      ~QuantumCircuit.if_test
      ~QuantumCircuit.initialize
      ~QuantumCircuit.inverse
      ~QuantumCircuit.iso
      ~QuantumCircuit.isometry
      ~QuantumCircuit.iswap
      ~QuantumCircuit.mcp
      ~QuantumCircuit.mcrx
      ~QuantumCircuit.mcry
      ~QuantumCircuit.mcrz
      ~QuantumCircuit.mct
      ~QuantumCircuit.mcu1
      ~QuantumCircuit.mcx
      ~QuantumCircuit.measure
      ~QuantumCircuit.measure_active
      ~QuantumCircuit.measure_all
      ~QuantumCircuit.ms
      ~QuantumCircuit.num_connected_components
      ~QuantumCircuit.num_nonlocal_gates
      ~QuantumCircuit.num_tensor_factors
      ~QuantumCircuit.num_unitary_factors
      ~QuantumCircuit.p
      ~QuantumCircuit.pauli
      ~QuantumCircuit.power
      ~QuantumCircuit.qasm
      ~QuantumCircuit.qbit_argument_conversion
      ~QuantumCircuit.qubit_duration
      ~QuantumCircuit.qubit_start_time
      ~QuantumCircuit.qubit_stop_time
      ~QuantumCircuit.r
      ~QuantumCircuit.rcccx
      ~QuantumCircuit.rccx
      ~QuantumCircuit.remove_final_measurements
      ~QuantumCircuit.repeat
      ~QuantumCircuit.reset
      ~QuantumCircuit.reverse_bits
      ~QuantumCircuit.reverse_ops
      ~QuantumCircuit.rv
      ~QuantumCircuit.rx
      ~QuantumCircuit.rxx
      ~QuantumCircuit.ry
      ~QuantumCircuit.ryy
      ~QuantumCircuit.rz
      ~QuantumCircuit.rzx
      ~QuantumCircuit.rzz
      ~QuantumCircuit.s
      ~QuantumCircuit.save_amplitudes
      ~QuantumCircuit.save_amplitudes_squared
      ~QuantumCircuit.save_clifford
      ~QuantumCircuit.save_density_matrix
      ~QuantumCircuit.save_expectation_value
      ~QuantumCircuit.save_expectation_value_variance
      ~QuantumCircuit.save_matrix_product_state
      ~QuantumCircuit.save_probabilities
      ~QuantumCircuit.save_probabilities_dict
      ~QuantumCircuit.save_stabilizer
      ~QuantumCircuit.save_state
      ~QuantumCircuit.save_statevector
      ~QuantumCircuit.save_statevector_dict
      ~QuantumCircuit.save_superop
      ~QuantumCircuit.save_unitary
      ~QuantumCircuit.sdg
      ~QuantumCircuit.set_density_matrix
      ~QuantumCircuit.set_matrix_product_state
      ~QuantumCircuit.set_stabilizer
      ~QuantumCircuit.set_statevector
      ~QuantumCircuit.set_superop
      ~QuantumCircuit.set_unitary
      ~QuantumCircuit.size
      ~QuantumCircuit.snapshot
      ~QuantumCircuit.snapshot_density_matrix
      ~QuantumCircuit.snapshot_expectation_value
      ~QuantumCircuit.snapshot_probabilities
      ~QuantumCircuit.snapshot_stabilizer
      ~QuantumCircuit.snapshot_statevector
      ~QuantumCircuit.squ
      ~QuantumCircuit.swap
      ~QuantumCircuit.sx
      ~QuantumCircuit.sxdg
      ~QuantumCircuit.t
      ~QuantumCircuit.tdg
      ~QuantumCircuit.tensor
      ~QuantumCircuit.to_gate
      ~QuantumCircuit.to_instruction
      ~QuantumCircuit.toffoli
      ~QuantumCircuit.u
      ~QuantumCircuit.u1
      ~QuantumCircuit.u2
      ~QuantumCircuit.u3
      ~QuantumCircuit.uc
      ~QuantumCircuit.ucrx
      ~QuantumCircuit.ucry
      ~QuantumCircuit.ucrz
      ~QuantumCircuit.unitary
      ~QuantumCircuit.while_loop
      ~QuantumCircuit.width
      ~QuantumCircuit.x
      ~QuantumCircuit.y
      ~QuantumCircuit.z



   .. rubric:: Attributes

   .. autoattribute:: ancillas
   .. autoattribute:: calibrations
   .. autoattribute:: clbits
   .. autoattribute:: data
   .. autoattribute:: extension_lib
   .. autoattribute:: global_phase
   .. autoattribute:: header
   .. autoattribute:: instances
   .. autoattribute:: metadata
   .. autoattribute:: num_ancillas
   .. autoattribute:: num_clbits
   .. autoattribute:: num_parameters
   .. autoattribute:: num_qubits
   .. autoattribute:: parameters
   .. autoattribute:: prefix
   .. autoattribute:: qubits
