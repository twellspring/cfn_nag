### [4.3.4](https://github.com/twellspring/cfn_nag/compare/v0.4.33...4.3.4) (12 July 2019)
- M  Test validation of PR title (Issue #[123](https://github.com/stelligent/cfn_nag/issues/123)) (PR #[2](https://github.com/twellspring/cfn_nag/pull/2))
- M Feature/191 release notes (PR #[1](https://github.com/twellspring/cfn_nag/pull/1))

### [v0.4.33](https://github.com/twellspring/cfn_nag/compare/v0.4.32...v0.4.33) (12 July 2019)

- C  Add rule to flag EBS volumes with KmsKeyID as a warning.  Refactor the EBS volume SSE rule to use the BooleanBaseRule (Issue #[262](https://github.com/stelligent/cfn_nag/issues/262))

### [v0.4.32](https://github.com/twellspring/cfn_nag/compare/v0.4.31...v0.4.32) (12 July 2019)
- M  update dev dockerfile and documentation (Issue #[244](https://github.com/stelligent/cfn_nag/issues/244)) (PR #[259](https://github.com/twellspring/cfn_nag/pull/259))

### [v0.4.31](https://github.com/twellspring/cfn_nag/compare/v0.4.30...v0.4.31) (10 July 2019)
- M  Feature/147 (Issue #[147](https://github.com/stelligent/cfn_nag/issues/147)) (PR #[243](https://github.com/twellspring/cfn_nag/pull/243))

### [v0.4.30](https://github.com/twellspring/cfn_nag/compare/v0.4.29...v0.4.30) (10 July 2019)
- M  Add new &#x27;colortxt&#x27; output_format, &#x27;txt&#x27; output_format no longer colorizes output (Issue #[242](https://github.com/stelligent/cfn_nag/issues/242)) (PR #[257](https://github.com/twellspring/cfn_nag/pull/257))

### [v0.4.29](https://github.com/twellspring/cfn_nag/compare/v0.4.28...v0.4.29) (5 July 2019)
- M Feature/adjust password base rule to work with sub properties (PR #[256](https://github.com/twellspring/cfn_nag/pull/256))

### [v0.4.28](https://github.com/twellspring/cfn_nag/compare/v0.4.27...v0.4.28) (2 July 2019)
- M Updating tests for RDS DB Instance resource (PR #[241](https://github.com/twellspring/cfn_nag/pull/241))

### [v0.4.27](https://github.com/twellspring/cfn_nag/compare/v0.4.26...v0.4.27) (2 July 2019)

- C  confirm e2e test shanking gem version (Issue #[251](https://github.com/stelligent/cfn_nag/issues/251))

### [v0.4.26](https://github.com/twellspring/cfn_nag/compare/v0.4.25...v0.4.26) (2 July 2019)

### [v0.4.25](https://github.com/twellspring/cfn_nag/compare/v0.4.24...v0.4.25) (2 July 2019)
- M fix dockerfile when gemfile.lock is not present (PR #[247](https://github.com/twellspring/cfn_nag/pull/247))

### [v0.4.24](https://github.com/twellspring/cfn_nag/compare/v0.4.23...v0.4.24) (2 July 2019)
- M Create consolidated Password rule (PR #[239](https://github.com/twellspring/cfn_nag/pull/239))

### [v0.4.23](https://github.com/twellspring/cfn_nag/compare/v0.4.22...v0.4.23) (24 June 2019)
- M Fail on not utilizing NoEcho for Password in AWS::DirectoryService::MicrosoftAD (PR #[235](https://github.com/twellspring/cfn_nag/pull/235))

### [v0.4.22](https://github.com/twellspring/cfn_nag/compare/v0.4.21...v0.4.22) (24 June 2019)
- M Fail on not utilizing NoEcho for Password in AWS::DMS::Endpoint (PR #[236](https://github.com/twellspring/cfn_nag/pull/236))

### [v0.4.21](https://github.com/twellspring/cfn_nag/compare/v0.4.20...v0.4.21) (22 June 2019)
- M adding dynamic reference tests and cleanup (PR #[237](https://github.com/twellspring/cfn_nag/pull/237))

### [v0.4.20](https://github.com/twellspring/cfn_nag/compare/v0.4.19...v0.4.20) (21 June 2019)

- C  add spec target (Issue #[233](https://github.com/stelligent/cfn_nag/issues/233))
- C  fix rubocop nags (Issue #[233](https://github.com/stelligent/cfn_nag/issues/233))

### [v0.4.19](https://github.com/twellspring/cfn_nag/compare/v0.4.18...v0.4.19) (21 June 2019)
- M Fail on not utilizing NoEcho for MasterUserPassword in AWS::Redshift::Cluster (PR #[232](https://github.com/twellspring/cfn_nag/pull/232))

### [v0.4.18](https://github.com/twellspring/cfn_nag/compare/v0.4.17...v0.4.18) (20 June 2019)
- M converted Make to Rake and added a few new commands (PR #[229](https://github.com/twellspring/cfn_nag/pull/229))

### [v0.4.17](https://github.com/twellspring/cfn_nag/compare/v0.4.16...v0.4.17) (20 June 2019)
- M Fail on not utilizing NoEcho for MasterUserPassword in AWS::RDS::DBCluster (PR #[228](https://github.com/twellspring/cfn_nag/pull/228))

### [v0.4.16](https://github.com/twellspring/cfn_nag/compare/v0.4.15...v0.4.16) (19 June 2019)
- M  More windows :io to :string fixes (Issue #[230](https://github.com/stelligent/cfn_nag/issues/230)) (PR #[231](https://github.com/twellspring/cfn_nag/pull/231))

### [v0.4.15](https://github.com/twellspring/cfn_nag/compare/v0.4.14...v0.4.15) (12 June 2019)
- M Remove need for RVM (PR #[227](https://github.com/twellspring/cfn_nag/pull/227))

### [v0.4.14](https://github.com/twellspring/cfn_nag/compare/v0.4.13...v0.4.14) (6 June 2019)

### [v0.4.13](https://github.com/twellspring/cfn_nag/compare/v0.4.12...v0.4.13) (6 June 2019)
- M  Fixes input-path opt on Windows (Issue #[140](https://github.com/stelligent/cfn_nag/issues/140)) (PR #[226](https://github.com/twellspring/cfn_nag/pull/226))

### [v0.4.12](https://github.com/twellspring/cfn_nag/compare/v0.4.11...v0.4.12) (6 June 2019)
- M  Fixes rule loading with Windows Command Prompt (Issue #[224](https://github.com/stelligent/cfn_nag/issues/224)) (PR #[225](https://github.com/twellspring/cfn_nag/pull/225))

### [v0.4.11](https://github.com/twellspring/cfn_nag/compare/v0.4.10...v0.4.11) (5 June 2019)
- M Prevent duplicate ids (PR #[221](https://github.com/twellspring/cfn_nag/pull/221))

### [v0.4.10](https://github.com/twellspring/cfn_nag/compare/v0.4.9...v0.4.10) (5 June 2019)
- M  Refactoring boolean rules to be more DRY (Issue #[211](https://github.com/stelligent/cfn_nag/issues/211)) (PR #[222](https://github.com/twellspring/cfn_nag/pull/222))

### [v0.4.9](https://github.com/twellspring/cfn_nag/compare/v0.4.8...v0.4.9) (3 June 2019)
- M  Restore output-type to cfn_nag (Issue #[214](https://github.com/stelligent/cfn_nag/issues/214)) (PR #[215](https://github.com/twellspring/cfn_nag/pull/215))

### [v0.4.8](https://github.com/twellspring/cfn_nag/compare/v0.4.7...v0.4.8) (31 May 2019)
- M Refactor CLI Interface, Add Scan fail-on-warnings (PR #[197](https://github.com/twellspring/cfn_nag/pull/197))

### [v0.4.7](https://github.com/twellspring/cfn_nag/compare/v0.4.6...v0.4.7) (31 May 2019)
- M Bugfix/account for false as string (PR #[219](https://github.com/twellspring/cfn_nag/pull/219))

### [v0.4.6](https://github.com/twellspring/cfn_nag/compare/v0.4.5...v0.4.6) (31 May 2019)
- M Feature/fail if enable key rotation false or absent (PR #[218](https://github.com/twellspring/cfn_nag/pull/218))

### [v0.4.5](https://github.com/twellspring/cfn_nag/compare/v0.4.4...v0.4.5) (30 May 2019)

### [v0.4.4](https://github.com/twellspring/cfn_nag/compare/v0.4.3...v0.4.4) (30 May 2019)

- C  Updating documentation for dockerhub (Issue #[205](https://github.com/stelligent/cfn_nag/issues/205))

### [v0.4.3](https://github.com/twellspring/cfn_nag/compare/v0.4.2...v0.4.3) (30 May 2019)
- M  Colorize text output format based on violation type (Issue #[146](https://github.com/stelligent/cfn_nag/issues/146)) (PR #[213](https://github.com/twellspring/cfn_nag/pull/213))

### [v0.4.2](https://github.com/twellspring/cfn_nag/compare/v0.4.1...v0.4.2) (29 May 2019)
- M S3BucketAccessLoggingRule (PR #[206](https://github.com/twellspring/cfn_nag/pull/206))

### [v0.4.1](https://github.com/twellspring/cfn_nag/compare/v0.4.0...v0.4.1) (29 May 2019)
- M Incorporating line number support from cfn-model (PR #[192](https://github.com/twellspring/cfn_nag/pull/192))

### [v0.4.0](https://github.com/twellspring/cfn_nag/compare/v0.3.98...v0.4.0) (3 May 2019)

### [v0.3.98](https://github.com/twellspring/cfn_nag/compare/v0.3.97...v0.3.98) (29 May 2019)

- C  Flip docker tag parmas (Issue #[204](https://github.com/stelligent/cfn_nag/issues/204))

### [v0.3.97](https://github.com/twellspring/cfn_nag/compare/v0.3.96...v0.3.97) (29 May 2019)
- M Push latest tag to Docker Hub (PR #[204](https://github.com/twellspring/cfn_nag/pull/204))

### [v0.3.96](https://github.com/twellspring/cfn_nag/compare/v0.3.95...v0.3.96) (28 May 2019)

- C  fix rule_id collision between efs and rds instance storage encryption rules (Issue #[208](https://github.com/stelligent/cfn_nag/issues/208))

### [v0.3.95](https://github.com/twellspring/cfn_nag/compare/v0.3.94...v0.3.95) (28 May 2019)

- C  document profiles and blacklist (Issue #[207](https://github.com/stelligent/cfn_nag/issues/207))

### [v0.3.94](https://github.com/twellspring/cfn_nag/compare/v0.3.93...v0.3.94) (28 May 2019)

- C  document profiles and blacklist (Issue #[207](https://github.com/stelligent/cfn_nag/issues/207))

### [v0.3.93](https://github.com/twellspring/cfn_nag/compare/v0.3.92...v0.3.93) (17 May 2019)
- M Update End To End Tests To Fail Appropriately (PR #[202](https://github.com/twellspring/cfn_nag/pull/202))

### [v0.3.92](https://github.com/twellspring/cfn_nag/compare/v0.3.91...v0.3.92) (14 May 2019)

### [v0.3.91](https://github.com/twellspring/cfn_nag/compare/v0.3.90...v0.3.91) (14 May 2019)
- M Fail on not utilizing NoEcho for MasterUserPassword in AWS::RDS::DBCluster (PR #[200](https://github.com/twellspring/cfn_nag/pull/200))

### [v0.3.90](https://github.com/twellspring/cfn_nag/compare/v0.3.89...v0.3.90) (14 May 2019)
- M Feature/end to end rspec tests (PR #[199](https://github.com/twellspring/cfn_nag/pull/199))

### [v0.3.89](https://github.com/twellspring/cfn_nag/compare/v0.3.88...v0.3.89) (8 May 2019)

### [v0.3.88](https://github.com/twellspring/cfn_nag/compare/v0.3.87...v0.3.88) (8 May 2019)

- C  the reference validator will ignore .Alias and .Version and .Anything in a ref and only consider the first token before the period (Issue #[115](https://github.com/stelligent/cfn_nag/issues/115))

### [v0.3.87](https://github.com/twellspring/cfn_nag/compare/v0.3.86...v0.3.87) (8 May 2019)
- M  adding rule and tests for batch jobdefiniton container properties to check for privileged&#x3D;true (Issue #[71](https://github.com/stelligent/cfn_nag/issues/71)) (PR #[195](https://github.com/twellspring/cfn_nag/pull/195))

### [v0.3.86](https://github.com/twellspring/cfn_nag/compare/v0.3.85...v0.3.86) (8 May 2019)

- C  bump cfn-model to fix serverless::function::CodeUri fail (and lock in the version of cfn-model) (Issue #[193](https://github.com/stelligent/cfn_nag/issues/193))

### [v0.3.85](https://github.com/twellspring/cfn_nag/compare/v0.3.84...v0.3.85) (8 May 2019)
- M Warn on MapPublicIpOnLaunch&#x3D;True in AWS::EC2::Subnet (PR #[194](https://github.com/twellspring/cfn_nag/pull/194))

### [v0.3.84](https://github.com/twellspring/cfn_nag/compare/v0.3.83...v0.3.84) (2 May 2019)
- M This commit fixes some rubocop nitpicks. (PR #[190](https://github.com/twellspring/cfn_nag/pull/190))
- M Feature/warn_when_resource_has_explicit_name (PR #[189](https://github.com/twellspring/cfn_nag/pull/189))

### [v0.3.83](https://github.com/twellspring/cfn_nag/compare/v0.3.82...v0.3.83) (2 May 2019)
- M DockerHub Push (PR #[188](https://github.com/twellspring/cfn_nag/pull/188))

### [v0.3.82](https://github.com/twellspring/cfn_nag/compare/v0.3.81...v0.3.82) (2 May 2019)
- M Add SimpleAD Rule, DRY Refactor (PR #[182](https://github.com/twellspring/cfn_nag/pull/182))

### [v0.3.81](https://github.com/twellspring/cfn_nag/compare/v0.3.80...v0.3.81) (26 April 2019)
- M Add fail-on-warnings option (PR #[185](https://github.com/twellspring/cfn_nag/pull/185))

### [v0.3.80](https://github.com/twellspring/cfn_nag/compare/v0.3.79...v0.3.80) (24 April 2019)
- M Hotfix RDS DBInstance With ClusterIdentifier (PR #[184](https://github.com/twellspring/cfn_nag/pull/184))

### [v0.3.79](https://github.com/twellspring/cfn_nag/compare/v0.3.78...v0.3.79) (23 April 2019)
- M Add RuboCop vendor directory exclusion (PR #[180](https://github.com/twellspring/cfn_nag/pull/180))

### [v0.3.78](https://github.com/twellspring/cfn_nag/compare/v0.3.77...v0.3.78) (23 April 2019)
- M Add CodeBuild::Project Missing EncryptionKey Warning (PR #[179](https://github.com/twellspring/cfn_nag/pull/179))

### [v0.3.77](https://github.com/twellspring/cfn_nag/compare/v0.3.76...v0.3.77) (23 April 2019)
- M Add Rudimentary Test Documentation (PR #[178](https://github.com/twellspring/cfn_nag/pull/178))

### [v0.3.76](https://github.com/twellspring/cfn_nag/compare/v0.3.75...v0.3.76) (19 April 2019)

- C  bump cfn-model to obtain new json parameter values substitution format (Issue #[154](https://github.com/stelligent/cfn_nag/issues/154))

### [v0.3.75](https://github.com/twellspring/cfn_nag/compare/v0.3.74...v0.3.75) (19 April 2019)
- M Add NeptuneDBCluster Storage Encryption Check (PR #[175](https://github.com/twellspring/cfn_nag/pull/175))

### [v0.3.74](https://github.com/twellspring/cfn_nag/compare/v0.3.73...v0.3.74) (19 April 2019)

- C  The main point of this commit is to add a global blacklist to suppress rules across a scan without considering resources (like the metadata suppression does). (Issue #[177](https://github.com/stelligent/cfn_nag/issues/177))

### [v0.3.73](https://github.com/twellspring/cfn_nag/compare/v0.3.72...v0.3.73) (18 April 2019)

- C  i shanked the merge (Issue #[170](https://github.com/stelligent/cfn_nag/issues/170))

### [v0.3.72](https://github.com/twellspring/cfn_nag/compare/v0.3.71...v0.3.72) (18 April 2019)

### [v0.3.71](https://github.com/twellspring/cfn_nag/compare/v0.3.70...v0.3.71) (18 April 2019)
- M Fixing various rubocop violations (PR #[174](https://github.com/twellspring/cfn_nag/pull/174))

### [v0.3.70](https://github.com/twellspring/cfn_nag/compare/v0.3.69...v0.3.70) (18 April 2019)
- M Refactoring for the following lint class cops (PR #[173](https://github.com/twellspring/cfn_nag/pull/173))

### [v0.3.69](https://github.com/twellspring/cfn_nag/compare/v0.3.68...v0.3.69) (18 April 2019)
- M Adding dockerfile for future DockerHub publishing (PR #[168](https://github.com/twellspring/cfn_nag/pull/168))

### [v0.3.68](https://github.com/twellspring/cfn_nag/compare/v0.3.67...v0.3.68) (13 April 2019)
- M Refactoring for Metrics/LineLength Iteration #1 (PR #[170](https://github.com/twellspring/cfn_nag/pull/170))

### [v0.3.67](https://github.com/twellspring/cfn_nag/compare/v0.3.66...v0.3.67) (13 April 2019)
- M Refactoring for Style/FrozenStringLiteralComment (PR #[171](https://github.com/twellspring/cfn_nag/pull/171))

### [v0.3.66](https://github.com/twellspring/cfn_nag/compare/v0.3.65...v0.3.66) (12 April 2019)
- M Refactoring for layout and whitespace violations (PR #[172](https://github.com/twellspring/cfn_nag/pull/172))

### [v0.3.65](https://github.com/twellspring/cfn_nag/compare/v0.3.64...v0.3.65) (12 April 2019)
- M Refactoring for Metrics/MethodLength (PR #[169](https://github.com/twellspring/cfn_nag/pull/169))

### [v0.3.64](https://github.com/twellspring/cfn_nag/compare/v0.3.63...v0.3.64) (11 April 2019)
- M Ignore Gemspec/RequiredRubyVersion for now (PR #[167](https://github.com/twellspring/cfn_nag/pull/167))
- M Open up ruby version for landing zone implementation (PR #[166](https://github.com/twellspring/cfn_nag/pull/166))

### [v0.3.63](https://github.com/twellspring/cfn_nag/compare/v0.3.62...v0.3.63) (11 April 2019)
- M Re-enabling rubocop as part of CI process (PR #[165](https://github.com/twellspring/cfn_nag/pull/165))

### [v0.3.62](https://github.com/twellspring/cfn_nag/compare/v0.3.61...v0.3.62) (11 April 2019)
- M Migrate to ruby 2.5.x (PR #[164](https://github.com/twellspring/cfn_nag/pull/164))

### [v0.3.61](https://github.com/twellspring/cfn_nag/compare/v0.3.60...v0.3.61) (9 April 2019)
- M Adding rule for EFS FileSystem encryption (PR #[158](https://github.com/twellspring/cfn_nag/pull/158))

### [v0.3.60](https://github.com/twellspring/cfn_nag/compare/v0.3.59...v0.3.60) (9 April 2019)
- M Adding rules for RDS storage encryption (PR #[157](https://github.com/twellspring/cfn_nag/pull/157))

### [v0.3.59](https://github.com/twellspring/cfn_nag/compare/v0.3.58...v0.3.59) (9 April 2019)
- M Adding custom rule for Workspaces encryption (PR #[160](https://github.com/twellspring/cfn_nag/pull/160))

### [v0.3.58](https://github.com/twellspring/cfn_nag/compare/v0.3.57...v0.3.58) (9 April 2019)
- M Adding custom rule for redshift cluster encryption (PR #[159](https://github.com/twellspring/cfn_nag/pull/159))

### [v0.3.57](https://github.com/twellspring/cfn_nag/compare/v0.3.56...v0.3.57) (4 April 2019)
- M Adding ElasticCache ReplicationGroup encryption rules (PR #[156](https://github.com/twellspring/cfn_nag/pull/156))

### [v0.3.56](https://github.com/twellspring/cfn_nag/compare/v0.3.55...v0.3.56) (22 March 2019)

- C  add documentation for JSON parameter structure (Issue #[154](https://github.com/stelligent/cfn_nag/issues/154))
- C  bump cfn-model and handle new JSON::ParserError when JSON is malformed or doesn&#x27;t meet the right format (Issue #[154](https://github.com/stelligent/cfn_nag/issues/154))

### [v0.3.55](https://github.com/twellspring/cfn_nag/compare/v0.3.54...v0.3.55) (18 February 2019)
- M Don&#x27;t evaluate potentially large string (PR #[151](https://github.com/twellspring/cfn_nag/pull/151))

### [v0.3.54](https://github.com/twellspring/cfn_nag/compare/v0.3.53...v0.3.54) (10 August 2018)

- C  bump cfn-model to fix this issue (Issue #[136](https://github.com/stelligent/cfn_nag/issues/136))

### [v0.3.53](https://github.com/twellspring/cfn_nag/compare/v0.3.52...v0.3.53) (28 April 2018)

- C  i short armed the unit testing here but...... --template-pattern in cfn_nag_scan is a full-on regular expression to control which files to scan.  default (without --template-pattern) is same as it ever was (Issue #[126](https://github.com/stelligent/cfn_nag/issues/126))

### [v0.3.52](https://github.com/twellspring/cfn_nag/compare/v0.3.51...v0.3.52) (27 April 2018)

- C  if Metadata/CloudFormation::Authentication is a roleName, it&#x27;s cool.  otherwise flag it as badness (Issue #[104](https://github.com/stelligent/cfn_nag/issues/104))

### [v0.3.51](https://github.com/twellspring/cfn_nag/compare/v0.3.50...v0.3.51) (27 April 2018)

- C  remove evil \ (Issue #[129](https://github.com/stelligent/cfn_nag/issues/129))

### [v0.3.50](https://github.com/twellspring/cfn_nag/compare/v0.3.49...v0.3.50) (27 April 2018)
- M remove codepipeline-lambda and update README to point to new repo (PR #[123](https://github.com/twellspring/cfn_nag/pull/123))

### [v0.3.49](https://github.com/twellspring/cfn_nag/compare/v0.3.48...v0.3.49) (27 April 2018)
- M Added rule suppression documentation to the README (PR #[125](https://github.com/twellspring/cfn_nag/pull/125))

### [v0.3.48](https://github.com/twellspring/cfn_nag/compare/v0.3.47...v0.3.48) (27 April 2018)

- C  Add a test to prove that non-InvokeFunction lambda permissions are properly flagged as violations. (Issue #[128](https://github.com/stelligent/cfn_nag/issues/128))

### [v0.3.47](https://github.com/twellspring/cfn_nag/compare/v0.3.46...v0.3.47) (30 March 2018)

- C  bump cfn-model to fix problems with over eager wildcard? predicate on Lambda Permission principal (Issue #[121](https://github.com/stelligent/cfn_nag/issues/121))

### [v0.3.46](https://github.com/twellspring/cfn_nag/compare/v0.3.45...v0.3.46) (30 March 2018)

### [v0.3.45](https://github.com/twellspring/cfn_nag/compare/v0.3.44...v0.3.45) (30 March 2018)

### [v0.3.44](https://github.com/twellspring/cfn_nag/compare/v0.3.43...v0.3.44) (30 March 2018)
- M fix, consistent stage name (PR #[120](https://github.com/twellspring/cfn_nag/pull/120))
- M Linting and pipeline (PR #[119](https://github.com/twellspring/cfn_nag/pull/119))

### [v0.3.43](https://github.com/twellspring/cfn_nag/compare/v0.3.42...v0.3.43) (30 March 2018)

### [v0.3.42](https://github.com/twellspring/cfn_nag/compare/v0.3.41...v0.3.42) (28 March 2018)
- M Linting method complexity (PR #[117](https://github.com/twellspring/cfn_nag/pull/117))

### [v0.3.41](https://github.com/twellspring/cfn_nag/compare/v0.3.40...v0.3.41) (28 March 2018)

### [v0.3.40](https://github.com/twellspring/cfn_nag/compare/v0.3.39...v0.3.40) (28 March 2018)

### [v0.3.39](https://github.com/twellspring/cfn_nag/compare/v0.3.38...v0.3.39) (28 March 2018)

### [v0.3.38](https://github.com/twellspring/cfn_nag/compare/v0.3.37...v0.3.38) (28 March 2018)

### [v0.3.37](https://github.com/twellspring/cfn_nag/compare/v0.3.36...v0.3.37) (28 March 2018)

### [v0.3.36](https://github.com/twellspring/cfn_nag/compare/v0.3.35...v0.3.36) (27 March 2018)

### [v0.3.35](https://github.com/twellspring/cfn_nag/compare/v0.3.34...v0.3.35) (27 March 2018)

### [v0.3.34](https://github.com/twellspring/cfn_nag/compare/v0.3.33...v0.3.34) (27 March 2018)

### [v0.3.33](https://github.com/twellspring/cfn_nag/compare/v0.3.32...v0.3.33) (27 March 2018)
- M Remove gemfile lock (PR #[116](https://github.com/twellspring/cfn_nag/pull/116))

### [v0.3.32](https://github.com/twellspring/cfn_nag/compare/v0.3.31...v0.3.32) (27 March 2018)

### [v0.3.31](https://github.com/twellspring/cfn_nag/compare/v0.3.30...v0.3.31) (23 March 2018)

### [v0.3.30](https://github.com/twellspring/cfn_nag/compare/v0.3.29...v0.3.30) (23 March 2018)

### [v0.3.29](https://github.com/twellspring/cfn_nag/compare/v0.3.28...v0.3.29) (23 March 2018)

### [v0.3.28](https://github.com/twellspring/cfn_nag/compare/v0.3.27...v0.3.28) (23 March 2018)

### [v0.3.27](https://github.com/twellspring/cfn_nag/compare/v0.3.25...v0.3.27) (23 March 2018)
- M Argf refactor (PR #[114](https://github.com/twellspring/cfn_nag/pull/114))

### [v0.3.25](https://github.com/twellspring/cfn_nag/compare/v0.3.24...v0.3.25) (20 March 2018)

- C  bump cfn-model for missing to/from port fix (Issue #[113](https://github.com/stelligent/cfn_nag/issues/113))

### [v0.3.24](https://github.com/twellspring/cfn_nag/compare/v0.3.23...v0.3.24) (19 March 2018)

- C  Bump cfn-model one more time - JSON array parameters cause ugly exception (Issue #[110](https://github.com/stelligent/cfn_nag/issues/110))

### [v0.3.23](https://github.com/twellspring/cfn_nag/compare/v0.3.22...v0.3.23) (17 March 2018)

- C  add rule for finding literal passwords in RDS instance.  flags literal, parameter that isn&#x27;t NoEcho or a parameter that has a default.  use the new parameters support in cfn-model (Issue #[49](https://github.com/stelligent/cfn_nag/issues/49))
- C  Bump cfn-model to get ability to substitute external JSON parmeters value files.  Add command line options (Issue #[110](https://github.com/stelligent/cfn_nag/issues/110))

### [v0.3.22](https://github.com/twellspring/cfn_nag/compare/v0.3.21...v0.3.22) (15 March 2018)
- M Custom rule to check publicly accessible property in RDS instance (PR #[109](https://github.com/twellspring/cfn_nag/pull/109))

### [v0.3.21](https://github.com/twellspring/cfn_nag/compare/v0.3.20...v0.3.21) (14 March 2018)

- C  Bump cfn-model version for fix of parsing JSON/YAML that is just an array (Issue #[108](https://github.com/stelligent/cfn_nag/issues/108))

### [v0.3.20](https://github.com/twellspring/cfn_nag/compare/v0.3.19...v0.3.20) (15 February 2018)

- C  Use the new LambdaPrincipal object to check for wildcard here.  The Principal can only be a string (or an integer) vs. a Hash like for Principal in IAM policies.  Strictly speaking int isn&#x27;t listed as being supported here, but it is. (Issue #[105](https://github.com/stelligent/cfn_nag/issues/105))

### [v0.3.19](https://github.com/twellspring/cfn_nag/compare/v0.3.18...v0.3.19) (10 February 2018)
- M Expanding Documentation (PR #[98](https://github.com/twellspring/cfn_nag/pull/98))

### [v0.3.18](https://github.com/twellspring/cfn_nag/compare/v0.3.17...v0.3.18) (11 January 2018)

- C  bump cfn-model to deal with custom resources with lower case type name (Issue #[99](https://github.com/stelligent/cfn_nag/issues/99))

### [v0.3.17](https://github.com/twellspring/cfn_nag/compare/v0.3.16...v0.3.17) (18 December 2017)

- C  bump model version to get fix (Issue #[95](https://github.com/stelligent/cfn_nag/issues/95))

### [v0.3.16](https://github.com/twellspring/cfn_nag/compare/v0.3.15...v0.3.16) (15 December 2017)

- C  bump version of cfn-model to get fix for some problems with Fn::If in iam resources and security groups (Issue #[93](https://github.com/stelligent/cfn_nag/issues/93))

### [v0.3.15](https://github.com/twellspring/cfn_nag/compare/v0.3.14...v0.3.15) (9 December 2017)

- C  add flag to isolate exceptions in custom rules (Issue #[91](https://github.com/stelligent/cfn_nag/issues/91))

### [v0.3.14](https://github.com/twellspring/cfn_nag/compare/v0.3.13...v0.3.14) (9 December 2017)

- C  fish the version out from the gem spec for the command line --version argument (for all bins) (Issue #[90](https://github.com/stelligent/cfn_nag/issues/90))

### [v0.3.13](https://github.com/twellspring/cfn_nag/compare/v0.3.12...v0.3.13) (9 December 2017)

- C  consider a syntax error exception from Psych for yaml/json parsing as a &quot;fatal&quot; violation and pass something more user friendly out to the user instead of a vulgar stack trace (Issue #[89](https://github.com/stelligent/cfn_nag/issues/89))

### [v0.3.12](https://github.com/twellspring/cfn_nag/compare/v0.3.11...v0.3.12) (9 December 2017)

- C  bump version of cfn-model to avoid parsing failure when load balancer/v2 or eni has a security groups reference to a List of ids or a CommaDelimitedList. (Issue #[88](https://github.com/stelligent/cfn_nag/issues/88))

### [v0.3.11](https://github.com/twellspring/cfn_nag/compare/v0.3.10...v0.3.11) (22 November 2017)

- C  First cut at experimental feature to ignore explicit rules on a given resource by using Metadata attribute. (Issue #[87](https://github.com/stelligent/cfn_nag/issues/87))

### [v0.3.10](https://github.com/twellspring/cfn_nag/compare/v0.3.9...v0.3.10) (15 November 2017)

- C  bump cfn-model to deal with missing VpcId in a SecurityGroup (Issue #[82](https://github.com/stelligent/cfn_nag/issues/82))

### [v0.3.9](https://github.com/twellspring/cfn_nag/compare/v0.3.8...v0.3.9) (7 November 2017)

- C  bump the version of cfn-model to avoid overly strict parsing of elastic load balancer&#x27;s policies in the case of Fn:If (Issue #[81](https://github.com/stelligent/cfn_nag/issues/81))

### [v0.3.8](https://github.com/twellspring/cfn_nag/compare/v0.3.7...v0.3.8) (2 November 2017)

- C  Bump the version of cfn-model so that EC2 instances with SecurityGroupIds that are a Ref to AWS::EC2::SecurityGroup::Id don&#x27;t cause a failure in parsing (Issue #[80](https://github.com/stelligent/cfn_nag/issues/80))

### [v0.3.7](https://github.com/twellspring/cfn_nag/compare/v0.3.6...v0.3.7) (31 October 2017)

- C  fix up some formatting on the readme (Issue #[45](https://github.com/stelligent/cfn_nag/issues/45))

### [v0.3.6](https://github.com/twellspring/cfn_nag/compare/v0.3.5...v0.3.6) (31 October 2017)

- C  first working cut at a lambda action that can be called direct from CodePipeline in order to invoke cfn-nag against artifacts. (Issue #[45](https://github.com/stelligent/cfn_nag/issues/45))

### [v0.3.5](https://github.com/twellspring/cfn_nag/compare/v0.3.4...v0.3.5) (18 October 2017)

- C  accommodate Encrypted as a String instead of expecting it to meet the specification that it is boolean (Issue #[78](https://github.com/stelligent/cfn_nag/issues/78))

### [v0.3.4](https://github.com/twellspring/cfn_nag/compare/v0.3.3...v0.3.4) (27 September 2017)

- C  upgrade cfn-model to not fail on network load balancers (and the fact that v2 LB can have subnets or subnet mapping to EIP) (Issue #[44](https://github.com/stelligent/cfn_nag/issues/44))

### [v0.3.3](https://github.com/twellspring/cfn_nag/compare/v0.3.2...v0.3.3) (22 September 2017)

- C  upgrade the model gem to fix issue with parsing IAM::Policy - update the gemspec (Issue #[43](https://github.com/stelligent/cfn_nag/issues/43))
- C  upgrade the model gem to fix issue with parsing IAM::Policy (Issue #[43](https://github.com/stelligent/cfn_nag/issues/43))

### [v0.3.2](https://github.com/twellspring/cfn_nag/compare/v0.3.1...v0.3.2) (26 August 2017)
- M adds support for loading a profile using the format for cfn_nag_rule (PR #[38](https://github.com/twellspring/cfn_nag/pull/38))

### [v0.3.1](https://github.com/twellspring/cfn_nag/compare/v0.3.0...v0.3.1) (15 August 2017)
- M  Add logo (Issue #[41](https://github.com/stelligent/cfn_nag/issues/41)) (PR #[40](https://github.com/twellspring/cfn_nag/pull/40))

### [v0.3.0](https://github.com/twellspring/cfn_nag/compare/v0.1.8...v0.3.0) (15 August 2017)

- C  upgrade cfn-model and make sure all the rules use the new model. (Issue #[37](https://github.com/stelligent/cfn_nag/issues/37))
- C  first draft at a migration guide (Issue #[41](https://github.com/stelligent/cfn_nag/issues/41))
- C  upgrade cfn-model and make sure all the rules use the new model. (Issue #[37](https://github.com/stelligent/cfn_nag/issues/37))

### [v0.1.8](https://github.com/twellspring/cfn_nag/compare/v0.1.7...v0.1.8) (19 July 2017)

- C  commit message was mangled for prior message. (Issue #[22](https://github.com/stelligent/cfn_nag/issues/22))

### [v0.1.7](https://github.com/twellspring/cfn_nag/compare/v0.1.6...v0.1.7) (17 July 2017)

- C  fix installation issues on Windoze because of :: in filenames in cfn-model (Issue #[36](https://github.com/stelligent/cfn_nag/issues/36))

### [v0.1.6](https://github.com/twellspring/cfn_nag/compare/v0.1.5...v0.1.6) (17 July 2017)

- C  fix installation issues on Windoze because of :: in filenames in cfn-model (Issue #[36](https://github.com/stelligent/cfn_nag/issues/36))

### [v0.1.5](https://github.com/twellspring/cfn_nag/compare/v0.1.4...v0.1.5) (17 July 2017)

- C  fix failure when specifying Tags in SecurityGroup (Issue #[35](https://github.com/stelligent/cfn_nag/issues/35))

### [v0.1.4](https://github.com/twellspring/cfn_nag/compare/v0.1.3...v0.1.4) (17 July 2017)

- C  add experimental support for jmespath. (Issue #[19](https://github.com/stelligent/cfn_nag/issues/19))

### [v0.1.3](https://github.com/twellspring/cfn_nag/compare/v0.1.2...v0.1.3) (14 July 2017)

- C  working through adding jmespath - found regression with cfn_nag_scan - streamline template discovery return values to be File (Issue #[19](https://github.com/stelligent/cfn_nag/issues/19))
- C  working through adding jmespath - found regression with cfn_nag_scan (Issue #[19](https://github.com/stelligent/cfn_nag/issues/19))

### [v0.1.2](https://github.com/twellspring/cfn_nag/compare/v0.1.1...v0.1.2) (14 July 2017)

- C  upgrade logging to 2.2.2 to make ruby 2.4 happy (Issue #[34](https://github.com/stelligent/cfn_nag/issues/34))

### [v0.1.1](https://github.com/twellspring/cfn_nag/compare/v0.1.0...v0.1.1) (14 July 2017)

- C  update the readme for some of the recent major rework (Issue #[23](https://github.com/stelligent/cfn_nag/issues/23))

### [v0.1.0](https://github.com/twellspring/cfn_nag/compare/v0.0.43...v0.1.0) (14 July 2017)

### [v0.0.43](https://github.com/twellspring/cfn_nag/compare/v0.0.42...v0.0.43) (18 May 2017)

- C  Deal with missing Action (when there&#x27;s a NotAction).  Regression from relaxing sqs:* to contains a *. (Issue #[32](https://github.com/stelligent/cfn_nag/issues/32))

### [v0.0.42](https://github.com/twellspring/cfn_nag/compare/v0.0.41...v0.0.42) (12 May 2017)

- C  I &quot;fixed&quot; W8 and W9 yesterday - the munged regex was ignoring just about everything so switched to endswith, but caused regression with non string CidrIp. (Issue #[31](https://github.com/stelligent/cfn_nag/issues/31))

### [v0.0.41](https://github.com/twellspring/cfn_nag/compare/v0.0.40...v0.0.41) (11 May 2017)

- C  the regular expression was apparently totally hosed for W8 and W9 and I never had a test in the first place, so bad on me.  Simplified the predicates to not rely on regular expressions with the backslash nightmare and in turn added tests to prove the expected behavior (Issue #[30](https://github.com/stelligent/cfn_nag/issues/30))

### [v0.0.40](https://github.com/twellspring/cfn_nag/compare/v0.0.39...v0.0.40) (11 May 2017)

- C  flag any wildcard in sqs actions as a violation (Issue #[27](https://github.com/stelligent/cfn_nag/issues/27))

### [v0.0.39](https://github.com/twellspring/cfn_nag/compare/v0.0.38...v0.0.39) (8 March 2017)

- C  expose the Parameters with an accessor (Issue #[28](https://github.com/stelligent/cfn_nag/issues/28))

### [v0.0.38](https://github.com/twellspring/cfn_nag/compare/v0.0.37...v0.0.38) (7 March 2017)

- C  don&#x27;t filter by profile when a raw/fatal violation happens like malformed JSON (Issue #[27](https://github.com/stelligent/cfn_nag/issues/27))

### [v0.0.37](https://github.com/twellspring/cfn_nag/compare/v0.0.36...v0.0.37) (17 February 2017)

- C  add some debug help (Issue #[16](https://github.com/stelligent/cfn_nag/issues/16))
- C  add some debug help (Issue #[16](https://github.com/stelligent/cfn_nag/issues/16))

### [v0.0.36](https://github.com/twellspring/cfn_nag/compare/v0.0.35...v0.0.36) (17 February 2017)

- C  clean up the presentation of the rules with the identifiers (Issue #[16](https://github.com/stelligent/cfn_nag/issues/16))

### [v0.0.35](https://github.com/twellspring/cfn_nag/compare/v0.0.34...v0.0.35) (16 February 2017)

- C  Add static rule identifiers for all rules, and then provide a profile/filtering mechanism (Issue #[16](https://github.com/stelligent/cfn_nag/issues/16))

### [v0.0.34](https://github.com/twellspring/cfn_nag/compare/v0.0.33...v0.0.34) (16 February 2017)

- C  fix regression on dump_rules from objectifying the custom rules registry (Issue #[17](https://github.com/stelligent/cfn_nag/issues/17))

### [v0.0.33](https://github.com/twellspring/cfn_nag/compare/v0.0.32...v0.0.33) (8 February 2017)

- C  doh.  i need some e2e tests against the cli here (Issue #[17](https://github.com/stelligent/cfn_nag/issues/17))

### [v0.0.32](https://github.com/twellspring/cfn_nag/compare/v0.0.31...v0.0.32) (8 February 2017)

- C  add a parser and rule registry so that custom rules can be added as poor man&#x27;s plugins (Issue #[17](https://github.com/stelligent/cfn_nag/issues/17))

### [v0.0.31](https://github.com/twellspring/cfn_nag/compare/v0.0.30...v0.0.31) (7 February 2017)

- C  add rule directory for add external json rules (Issue #[17](https://github.com/stelligent/cfn_nag/issues/17))
- C  fix half-axxed copy-paste error (Issue #[17](https://github.com/stelligent/cfn_nag/issues/17))
- C  helps to commit the test data (Issue #[17](https://github.com/stelligent/cfn_nag/issues/17))

### [v0.0.30](https://github.com/twellspring/cfn_nag/compare/v0.0.29...v0.0.30) (24 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.29](https://github.com/twellspring/cfn_nag/compare/v0.0.28...v0.0.29) (23 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.28](https://github.com/twellspring/cfn_nag/compare/v0.0.27...v0.0.28) (23 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.27](https://github.com/twellspring/cfn_nag/compare/v0.0.26...v0.0.27) (23 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.26](https://github.com/twellspring/cfn_nag/compare/v0.0.25...v0.0.26) (21 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.25](https://github.com/twellspring/cfn_nag/compare/v0.0.24...v0.0.25) (20 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.24](https://github.com/twellspring/cfn_nag/compare/v0.0.23...v0.0.24) (20 January 2017)

- C  a little creative hacking on jruby.  can&#x27;t look for file/resources in a jar conveniently from what i can see so.... make explicity just for our jruby/lambda experiments (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.23](https://github.com/twellspring/cfn_nag/compare/v0.0.22...v0.0.23) (20 January 2017)

- C  yech.  some debug info for a downstream component (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))
- C  yech.  some debug info for a downstream component (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.22](https://github.com/twellspring/cfn_nag/compare/v0.0.21...v0.0.22) (20 January 2017)

- C  expose audit_template for an experiment (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.21](https://github.com/twellspring/cfn_nag/compare/v0.0.20...v0.0.21) (20 January 2017)

- C  remove cruft (Issue #[24](https://github.com/stelligent/cfn_nag/issues/24))

### [v0.0.20](https://github.com/twellspring/cfn_nag/compare/v0.0.19...v0.0.20) (20 January 2017)
- M Issue 18 resolved (PR #[21](https://github.com/twellspring/cfn_nag/pull/21))

### [v0.0.19](https://github.com/twellspring/cfn_nag/compare/v0.0.18...v0.0.19) (24 March 2016)

- C  add license and homepage to the gem spec (Issue #[15](https://github.com/stelligent/cfn_nag/issues/15))

### [v0.0.18](https://github.com/twellspring/cfn_nag/compare/v0.0.17...v0.0.18) (2 March 2016)

- C  first crack at this.  it&#x27;s not quite complete.  at the very least the resource field isn&#x27;t considered in the rule matching.  i can probably confuse it with other things too though... need to double back with wider set of bucket policies from the real world (Issue #[11](https://github.com/stelligent/cfn_nag/issues/11))

### [v0.0.17](https://github.com/twellspring/cfn_nag/compare/v0.0.16...v0.0.17) (2 March 2016)

- C  add cfn_nag_rules binary to dump a list of warnings and failing violations supported by the tool (Issue #[12](https://github.com/stelligent/cfn_nag/issues/12))

### [v0.0.16](https://github.com/twellspring/cfn_nag/compare/v0.0.15...v0.0.16) (1 March 2016)

- C  add support for fishing out various wildcards from the different resource policies in SQS, SNS and S3 (Issue #[9](https://github.com/stelligent/cfn_nag/issues/9))

### [v0.0.15](https://github.com/twellspring/cfn_nag/compare/v0.0.14...v0.0.15) (29 February 2016)

- C  add nags for a few possibly funky things with Lambda permissions (Issue #[8](https://github.com/stelligent/cfn_nag/issues/8))

### [v0.0.14](https://github.com/twellspring/cfn_nag/compare/v0.0.13...v0.0.14) (29 February 2016)

- C  look for a cloud front distribution without logging configured (Issue #[7](https://github.com/stelligent/cfn_nag/issues/7))

### [v0.0.13](https://github.com/twellspring/cfn_nag/compare/v0.0.12...v0.0.13) (29 February 2016)

- C  hunt out obviously insecure ACL on S3 bucket (Issue #[6](https://github.com/stelligent/cfn_nag/issues/6))

### [v0.0.12](https://github.com/twellspring/cfn_nag/compare/v0.0.11...v0.0.12) (29 February 2016)

- C  add warnings for ELB without access logging configured or enabled (Issue #[5](https://github.com/stelligent/cfn_nag/issues/5))
- C  expose the results instead of just the count so we have a better vector for asserting the proper results. (Issue #[4](https://github.com/stelligent/cfn_nag/issues/4))

### [v0.0.11](https://github.com/twellspring/cfn_nag/compare/v0.0.10...v0.0.11) (29 February 2016)

- C  add a warning about using the Authentication metadata to store credentials in the template itself (Issue #[4](https://github.com/stelligent/cfn_nag/issues/4))

### [v0.0.10](https://github.com/twellspring/cfn_nag/compare/v0.0.9...v0.0.10) (26 February 2016)

- C  switch to WARN/FAIL for consistency with other tooling (Issue #[3](https://github.com/stelligent/cfn_nag/issues/3))

### [v0.0.9](https://github.com/twellspring/cfn_nag/compare/v0.0.8...v0.0.9) (26 February 2016)

- C  add rule to look for missing or false Encrypted bit on an EBS volume (Issue #[2](https://github.com/stelligent/cfn_nag/issues/2))

### [v0.0.8](https://github.com/twellspring/cfn_nag/compare/v0.0.7...v0.0.8) (25 February 2016)

- C  helps to run unit tests after a change.  changing to :io -&gt; File broke the tests themselves (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))
- C  make sure an invalid json file doesn&#x27;t throw a wrench in a &quot;batch&quot; lint-ing (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))

### [v0.0.7](https://github.com/twellspring/cfn_nag/compare/v0.0.6...v0.0.7) (25 February 2016)

- C  Add support for scanning a directory for .json and .template files and aggregating the results (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))

### [v0.0.6](https://github.com/twellspring/cfn_nag/compare/v0.0.5...v0.0.6) (25 February 2016)

- C  wipe out the templates if already there (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))

### [v0.0.5](https://github.com/twellspring/cfn_nag/compare/v0.0.4...v0.0.5) (24 February 2016)

- C  lock in the ruby version to 2.2 (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))

### [v0.0.4](https://github.com/twellspring/cfn_nag/compare/v0.0.3...v0.0.4) (24 February 2016)

- C  setup automation to publish to rubygems (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))
- C  remove dopey duplication of line (Issue #[1](https://github.com/stelligent/cfn_nag/issues/1))

### [v0.0.3](https://github.com/twellspring/cfn_nag/compare/v0.0.2...v0.0.3) (17 February 2016)

### [v0.0.2](https://github.com/twellspring/cfn_nag/compare/v0.0.1...v0.0.2) (17 February 2016)

### [v0.0.1]() (16 February 2016)
