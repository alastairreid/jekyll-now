---
layout: paper
abstract: |
    High-throughput, low-power Software Defined Radio(SDR)
    solutions require multi-core SIMD DSP processors to meet
    real-time performance requirements. Given the difficulty in
    programming traditional DSPs, these new multi-core signal
    processors provide even greater challenges for programmers and
    compilers. In this paper, we describe SPEX, a programming
    language which is aimed at narrowing the semantic gap between
    the description of complex SDR systems and their
    implementations. SPEX supports three different types of
    programming semantics, allowing SDR solutions to be developed
    with a divide-and-conquer approach. For DSP algorithm
    kernels, SPEX is able to support DSP arithmetics and
    first-class vector and matrix variables with sequential
    language semantics. From wireless protocol channels, it is able
    to support sequences of data-processing computations with
    dataflow language semantics. And for protocol systems, it is
    able to support real-time deadlines and concurrent executions
    with synchronous language semantics. The design choices are
    motivated by our experience implementing W-CDMA protocol on
    a reprogrammable substrate. In the paper, we also briefly
    explain SPEX's compilation strategies.
affiliation: ARM Ltd and University of Michigan
ar_file: SDR_06
ar_shortname: SDR 06
author: Yuan Lin, Robert Mullenix, Mark Woh, Scott Mahlke, Trevor Mudge Alastair Reid, Krisztián Flautner
booktitle: Software Defined Radio Technical Conference and Product Exposition
day: 13-17
file: lin-sdr06.pdf
location: Orlando, FL, USA
month: November
title: SPEX A programming language for software defined radio
year: 2006
ENTRYTYPE: inproceedings
ID: confSDRLinMW2006
bibtex: |
    @inproceedings{conf:SDR:LinMW2006
        , abstract = {High-throughput, low-power Software Defined Radio(SDR)
    solutions require multi-core SIMD DSP processors to meet
    real-time performance requirements. Given the difficulty in
    programming traditional DSPs, these new multi-core signal
    processors provide even greater challenges for programmers and
    compilers. In this paper, we describe SPEX, a programming
    language which is aimed at narrowing the semantic gap between
    the description of complex SDR systems and their
    implementations. SPEX supports three different types of
    programming semantics, allowing SDR solutions to be developed
    with a divide-and-conquer approach. For DSP algorithm
    kernels, SPEX is able to support DSP arithmetics and
    first-class vector and matrix variables with sequential
    language semantics. From wireless protocol channels, it is able
    to support sequences of data-processing computations with
    dataflow language semantics. And for protocol systems, it is
    able to support real-time deadlines and concurrent executions
    with synchronous language semantics. The design choices are
    motivated by our experience implementing W-CDMA protocol on
    a reprogrammable substrate. In the paper, we also briefly
    explain SPEX\textquotesingle s compilation strategies.}
        , affiliation = {ARM Ltd and University of Michigan}
        , ar_file = {SDR_06}
        , ar_shortname = {SDR 06}
        , author = {Yuan Lin and Robert Mullenix and Mark Woh and Scott Mahlke
    and Trevor Mudge Alastair Reid and Kriszti{\'a}n Flautner}
        , booktitle = {Software Defined Radio Technical Conference and Product Exposition}
        , day = {13-17}
        , file = {lin-sdr06.pdf}
        , location = {Orlando, FL, USA}
        , month = {November}
        , title = {S{P}EX: {A} programming language for software defined radio}
        , year = {2006}
    }
---