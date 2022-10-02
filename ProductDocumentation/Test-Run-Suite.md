##### Project

::[PROJECT-NAME](Home)

##### Internal Release Number

::X.Y.Z

##### Related Documents

- [QA Plan](QA-Plan) > Test Run Suite
- [Test suite](Test-Suite)
- ::LINKS TO RELEVANT STANDARDS
- ::LINKS TO OTHER DOCUMENTS

---

**Process impact:** This is a test run log for manual system testing. A
test run is logged whenever the manual system test suite is carried out.
The log overview helps visualize the set of system configurations that
have been tested and those that have not. Clearly understanding the
degree to which the system has been tested helps to assess progress,
assess risk, and focus ongoing testing efforts.

*TODO:*

- *Review the [target audience](Target-and-Benefits),
  [environmental requirements](SRS#environmental), and [possible
  deployments](Design-Architecturel#deployment) to understand the
  set of possible system configurations that could be tested.*
- *Use a table or list to describe that set of possible configurations.
  Mark each possibility with Pending, N/A, or Waived.*
- *Track each test run with an issue in the issue tracker or an item in
  the [test-runs](Test-Runs) document.*
- *Periodically review the set of possible system configurations to
  identify any additional needed test runs.*

### ::Test Runs by Operating System and Browser

| OS \ Browser   | IE                                       | Firefox                          | Safari                           | Chrome    | other   |
|----------------|------------------------------------------|----------------------------------|----------------------------------|-----------|---------|
| ::Windows      | ::[Passed](Test-Runs#TR-01)         | ::[Passed](Test-Runs#TR-02) | ::N/A                            | ::Pending | ::N/A   |
| ::Linux        | ::N/A                                    | ::[Passed](Test-Runs#TR-03) | ::Pending                        | ::Pending | ::N/A   |
| ::Mac          | ::[FAILED](Test-Runs#TR-10)         | ::Pending                        | ::[Passed](Test-Runs#TR-11) | ::Pending | ::N/A   |
| ::iOS          | ::N/A                                    | ::N/A                            | ::Pending                        | ::N/A     | ::N/A   |
| ::Android      | ::N/A                                    | ::N/A                            | ::Pending                        | ::Pending | ::N/A   |

### ::Test Runs by Locale

*TIP: Use this outline to guide the testing of internationalized
applications. Each locale indicates a native language as well as formats
for presenting money, dates, times, etc.*

- ::English US: [Passed](Test-Runs#TR-00)
- ::English UK: [Passed](Test-Runs#TR-01)
- ::English CA: [Passed](Test-Runs#TR-02)
- ::Japanese: [Passed](Test-Runs#TR-10)
- ::Spanish: Pending
- ::Russian: Pending
- ::German: Pending
- ::French: Pending
- ::French CA: Waived, French + English Canadian is good enough

### ::Test Runs by Hardware Configuration

*TIP: Use this outline for products that depend on specific hardware.
E.g., a disk crash recovery product would depend on the type of drive, a
game might depend on processor speed and graphics cards, other products
might depend on memory or other hardware specs.*

- ::PCs
  - ::IDE drive: Pending
  - ::EIDE drive: Waived because we only use IDE features
  - ::ATA drive: [Passed](Test-Runs#TR-00)
  - ::SCSI drive: [Passed](Test-Runs#TR-01)
  - ::SATA drive: [Passed](Test-Runs#TR-02)
  - ::USB drive: [FAILED](Test-Runs#TR-03)
- ::Macs
  - ::EIDE drive: [Passed](Test-Runs#TR-10)
  - ::SCSI drive: [Passed](Test-Runs#TR-11)
  - ::Firewire drive: Pending
  - ::USB drive: [FAILED](Test-Runs#TR-12)
